Here’s a clean, professional, and properly formatted **README.md** for your
**Online Food Ordering System (Spring Boot + Angular + MySQL)** project — perfect for GitHub or your resume portfolio 👇

---

# 🍽️ Online Food Ordering System (Spring Boot + Angular + MySQL)

## 🧠 Overview

The **Online Food Ordering System** is a full-stack web application developed using **Spring Boot**, **Angular**, and **MySQL**, following the **MVC (Model-View-Controller)** architecture.
It allows users to browse food items, add them to a cart, and place orders, while merchants can manage their menus dynamically.

---

## 🚀 Features

### 👤 For Users

* Register or log in securely
* Browse the menu and view food details
* Add items to the cart and proceed to payment
* Make purchases — the database automatically updates the item quantity

### 🛒 For Merchants

* Log in or register as a merchant
* View, add, or update food items and quantities
* Real-time menu updates using RESTful APIs (no page reload needed)

---

## 🧩 Technologies Used

| Layer                    | Technology                                |
| ------------------------ | ----------------------------------------- |
| **Frontend (View)**      | Angular 8 with Routing                    |
| **Backend (Controller)** | Spring Boot v2.1.6                        |
| **Database (Model)**     | MySQL                                     |
| **ORM Framework**        | Java Persistence API (JPA)                |
| **API Communication**    | REST APIs (Angular ↔ Spring Boot ↔ MySQL) |

**Port Configuration:**

* Angular → `4200`
* Spring Boot → `8080`
* MySQL → `3306`

---

## ⚙️ Software Requirements

* **Java 7** or above
* **MySQL Server**
* **Node.js** and **npm**

---

## 🧾 Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AkashGowda0/Online-Food-Ordering-System-Spring-Boot-Angular-MySQL.git
   ```

2. **Backend Setup (Spring Boot):**

   * Import the project into your IDE (IntelliJ, Eclipse, etc.)
   * Configure your MySQL database in `application.properties`
   * Run the application (`port:8080`)

3. **Frontend Setup (Angular):**

   ```bash
   cd frontend
   npm install
   ng serve
   ```

   Runs on `http://localhost:4200`

4. **Database Setup:**

   * Start MySQL server
   * Create the required schema and tables (auto-generated via JPA)

---

## 🔐 Default Login Credentials

| Role         | Username | Password |
| ------------ | -------- | -------- |
| **Merchant** | merchant | merchant |
| **User**     | user     | user     |

---

## 💡 How It Works

* Users and merchants can register or log in from the homepage.
* Users can view available food items and place orders securely.
* Upon payment, the database updates automatically to reflect purchased quantities.
* Merchants can dynamically update their menu, and changes reflect instantly using REST APIs without reloading the page.

---

## 🧑‍💻 Developer

**Author:** Akash Gowda
**GitHub Repository:** [Online Food Ordering System - Spring Boot, Angular, MySQL](https://github.com/AkashGowda0/Online-Food-Ordering-System-Spring-Boot-Angular-MySQL)

---

Would you like me to make a **shorter version (2–3 paragraphs)** of this README — suitable for including inside your **resume project description**?
