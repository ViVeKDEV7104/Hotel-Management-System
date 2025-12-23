HOTEL MANAGEMENT SYSTEM

Overview
This is a console-based Hotel Management System** developed in Java. It uses file-based I/O to store and retrieve hotel data such as guest information, bookings, and billing. The system is designed to ensure modularity, error-handling, and ease of use.

---

Core Features
- Guest check-in and check-out
- Room availability management
- Billing and receipt generation
- File-based storage using I/O streams
- Admin menu and secure access

---

Implementation Guidelines

### 🔹 Core Feature Implementation 
All functionalities have been implemented as per project requirements, including:
- Room booking
- Room cancellation
- View occupied/available rooms
- Guest information storage

### 🔹 Error Handling & Robustness 
- Input validations for date, room type, and guest details
- Graceful handling of invalid or missing files
- Prevents system crash on unexpected user behavior

### 🔹 Integration of Components 
- Seamless interaction between modules (Booking, Billing, Room Management)
- Shared utility functions for I/O and validation

### 🔹 Event Handling & Processing 
- User interactions are processed via efficient console menus
- Switch-case based navigation with minimal input lag

### 🔹 Data Validation 
- Name, phone number, and date formats validated
- Input constraints are applied on booking entries

### 🔹 Code Quality & Innovation 
- Code is modular, cleanly commented, and uses OOP principles
- Innovative features: auto-generated receipts, color-coded CLI feedback (optional)

---

---

## 🔬 Testing & Validation

✔ All major features tested  
✔ Invalid inputs tested (empty names, incorrect formats)  
✔ File data persists between runs  
✔ No runtime exceptions observed

---


