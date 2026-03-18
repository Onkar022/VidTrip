# 🌍✈️ VidTrip - Travel Planner & Expense Manager

<img width="506" height="506" alt="icon" src="https://github.com/user-attachments/assets/deb9eb1d-f093-488d-93b8-732fb668e2c5" />


**VidTrip** is a feature-rich, native Android application designed to be your ultimate travel companion for exploring the beautiful Vidarbha region. It helps users discover new places, book accommodations, intelligently plan detailed trip itineraries, and seamlessly manage travel expenses.

> **🔒 Project Status:** This repository serves as a public showcase and portfolio piece. The source code is currently kept private. If you are a recruiter or developer interested in discussing the codebase, architecture, or potential collaboration, please feel free to reach out!

---

## 🌟 Key Features

* **🗺️ Intelligent Trip Planner:** A powerful routing engine (**PlannerEngine**) that calculates optimized travel routes using the Nearest Neighbor algorithm and the Haversine formula.
* **💰 Dynamic Fare Calculation:** Detailed travel cost estimation factoring in transport modes (Bus, Train) and demographic discounts (e.g., age/gender).
* **🏨 Place & Hotel Discovery:** Explore tourist destinations with entry fees, best times to visit, and nearby hotels.
* **📊 Expense Management:** Track and manage trip budgets with categorized expense items.
* **🔐 Role-Based Access Control (RBAC):**
  * **User:** Manage profiles, plan trips, and leave reviews.
  * **Admin:** Dedicated dashboard to manage the catalog of places, hotels, and routes.
* **📍 Interactive Maps:** Full integration with Google Maps and Location Services.

---

## 📱 App Showcase

*(Drag and drop screenshots or short GIFs of your app running here. A table layout works great for this!)*

| Home Screen | Trip Planner | Expense Tracker |
| :---: | :---: | :---: |
| ![WhatsApp Image 2026-03-09 at 1 16 44 PM](https://github.com/user-attachments/assets/3f312db8-fae6-472b-8299-fbbb4d3dee2e)| ![WhatsApp Image 2026-03-07 at 6 30 50 PM](https://github.com/user-attachments/assets/45c9a1fc-be20-467e-bf45-6cd2128f7d45)|![WhatsApp Image 2026-03-07 at 6 30 49 PM](https://github.com/user-attachments/assets/4292c931-dfc4-4936-915e-c64383f6f4db)|

---

## 🏗️ Architecture & Tech Stack

VidTrip was built using modern Android development best practices, adhering strictly to **Clean Architecture** and the **MVVM** design pattern to ensure scalability and maintainability.

### Frontend (Android)
* **Language:** Kotlin (100%)
* **Architecture:** MVVM + Clean Architecture principles
* **Dependency Injection:** Dagger Hilt
* **Asynchrony:** Coroutines & Flow
* **Navigation:** Jetpack Navigation (Single Activity Architecture)
* **Local Storage:** Room Database & DataStore
* **Networking & UI:** Ktor Client & Glide

### Backend & Cloud (Supabase)
* **Database:** PostgreSQL with secure Row Level Security (RLS).
* **Authentication:** Supabase Auth for seamless user login and RBAC.
* **Storage:** Cloud storage buckets for secure imagery hosting.

---

## 👨‍💻 Meet the Developer

**Onkar Mantri** - Lead Developer

I am a software developer currently in my 6th semester of Computer Engineering, passionate about building robust, scalable mobile applications. 

* **Connect with me on LinkedIn:** *(Add your LinkedIn link here)*
* **Email:** *(mantrionkar22@gmail.com)*
*
