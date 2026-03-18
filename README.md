# VidTrip 🌍✈️

VidTrip is a feature-rich, native Android application designed to be your ultimate travel companion. It helps users discover new places, book accommodations, intelligently plan detailed trip itineraries, and seamlessly manage travel expenses.

## 🌟 Key Features

* **Intelligent Trip Planner:** A powerful routing engine (**PlannerEngine**) that calculates optimized travel routes using the Nearest Neighbor algorithm and Haversine formula.
* **Dynamic Fare Calculation:** Detailed travel cost estimation factoring in transport modes (Bus, Train) and demographics (e.g., age/gender discounts).
* **Place & Hotel Discovery:** Explore tourist destinations with entry fees, best times to visit, and nearby hotels.
* **Expense Management:** Track and manage trip expenses with categorized items.
* **Role-Based Access Control (RBAC):** * **User:** Manage profiles, plan trips, and leave reviews.
    * **Admin:** Dashboard to control the catalog of places, hotels, and routes.
* **Interactive Maps:** Full integration with Google Maps and Location Services.

## 🏗️ Architecture & Tech Stack

VidTrip adheres strictly to **Clean Architecture** and the **MVVM** design pattern. 

### Frontend (Android)
* **Language:** Kotlin (100%)
* **Dependency Injection:** Dagger Hilt
* **Asynchrony:** Coroutines & Flow
* **Navigation:** Jetpack Navigation (Single Activity)
* **Local Storage:** Room Database & DataStore
* **Networking:** Ktor Client & Glide

### Backend (Supabase)
* **Database:** PostgreSQL with Row Level Security (RLS).
* **Authentication:** Supabase Auth.
* **Storage:** Secure buckets for imagery.

## 🚀 Getting Started

### Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Onkar022/VidTrip.git](https://github.com/Onkar022/VidTrip.git)
    ```

2.  **Configure Supabase:**
    * Run the provided `supabase_schema.sql` in your Supabase SQL Editor.
    * Create storage buckets: `hotel-images` (Private) and `place_images` (Public).

3.  **API Keys:**
    * Add your `SUPABASE_URL`, `SUPABASE_KEY`, and `MAPS_API_KEY` to your `local.properties` or `build.gradle.kts` as specified in the project configuration.

## 📂 Project Structure
* `ui/`: Fragments and ViewModels grouped by feature.
* `logic/`: Core business logic (PlannerEngine).
* `data/`: Repositories, Room, and Supabase configurations.

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
