# Hotel Management System

A Java-based Hotel Management System developed as a second semester academic project.  
The application uses **JDBC** to interact with a **MySQL database** and allows efficient management of hotel operations such as room booking, customer records, and check-in/check-out processes.

---

## 📌 Features
- Add and manage customer details  
- View available rooms  
- Book rooms for customers  
- Check-out and update room availability  
- Display booking and customer records  
- Database-driven operations using JDBC  

---

## 🛠 Tech Stack
- **Programming Language:** Java  
- **Database:** MySQL  
- **Connectivity:** JDBC  
- **Tools:** VS Code / IntelliJ IDEA, MySQL Workbench  

---

## 🗂 Database Schema (Overview)
- **Customers Table**
  - customer_id
  - name
  - phone
  - email

- **Rooms Table**
  - room_id
  - room_type
  - price
  - availability_status

- **Bookings Table**
  - booking_id
  - customer_id
  - room_id
  - check_in_date
  - check_out_date

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/hotel-management-system.git
