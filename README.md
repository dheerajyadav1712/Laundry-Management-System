# 🧺 Laundry Management System

A modern and user-friendly web-based **Laundry Management System** built with **HTML, CSS, JavaScript, PHP**, and **MySQL**, hosted on the **WAMP Server**. This system streamlines laundry service operations for both **customers** and **administrators**, providing a seamless experience from order placement to delivery.

---

## 🚀 Key Features

### 👤 Customer Panel
- ✅ User Registration & Login
- 🧾 Place Laundry Orders with Item & Quantity Details
- 🧼 Choose Services (Washing, Ironing, Dry Cleaning, etc.)
- 📦 Track Order Status (Received → In Process → Ready → Delivered)
- 📚 View Past Order History
- 💵 Pay via **Cash on Delivery (COD)**

### 🛠️ Admin Panel
- 🔐 Secure Admin Login
- 👥 Manage Customers & Orders
- 📋 Update Laundry Order Status
- 🧾 Add, Edit & Delete Services with Pricing
- 📊 Generate Reports (Daily/Weekly/Monthly)
- 💬 Manage Customer Feedback

---

## 🧰 Technology Stack

| Layer      | Technology           |
|------------|----------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | PHP                  |
| Database   | MySQL                |
| Server     | WAMP (Apache + MySQL + PHP) |

---

## 📁 Project Folder Structure



```

laundry-management/
├── index.php
├── login.php
├── register.php
├── dashboard.php
├── place\_order.php
├── order\_status.php
├── order\_history.php
├── feedback.php
├── admin/
│   ├── dashboard.php
│   ├── manage\_orders.php
│   ├── manage\_services.php
│   └── manage\_customers.php
├── css/
├── js/
├── includes/
│   ├── db.php
│   ├── auth.php
│   └── functions.php
└── sql/
└── database.sql

````


---

## 🗃️ Database Schema Overview

- **`users`** – Stores customer account and contact info  
- **`orders`** – Contains order details, status updates, and timestamps  
- **`services`** – Holds data about available laundry services and pricing  
- **`feedback`** – Captures feedback provided by customers  
- **`admins`** – Admin credentials and access information  

---

## ⚙️ Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dheerajyadav1712/laundry-management-system.git
   ```


2. **Move to WAMP Directory**
   Place the project folder inside:

   ```
   C:/wamp64/www/
   ```

3. **Import the Database**

   * Start WAMP and open **phpMyAdmin**
   * Create a new database, e.g., `laundry_db`
   * Import the SQL file located at:

     ```
     sql/database.sql
     ```

4. **Configure Database Connection**

   * Edit the file: `includes/db.php`
   * Update with your MySQL credentials:

     ```php
     $conn = new mysqli("localhost", "root", "", "laundry_db");
     ```

5. **Launch the Application**
   Open your browser and go to:

   ```
   http://localhost/laundry-management-system/
   ```

---

## 🙌 Contribution Guidelines

We welcome contributions! Feel free to:

* Report bugs
* Suggest features
* Submit pull requests

📌 For major changes, open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Developed with ❤️ by [Dheeraj Yadav](https://github.com/dheerajyadav1712)**

```

