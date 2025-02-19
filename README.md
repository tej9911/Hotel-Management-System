# 🏨 Hotel Management System

## 📌 Overview
The **Hotel Management System** is a **Java Swing-based** application that manages various hotel operations such as **room booking, employee management, customer check-in/check-out, and billing**. The project is built using **Java**, **Swing for GUI**, and **MySQL for database management**.

## 🚀 Features
- 🏢 **Hotel Dashboard** - A central dashboard to manage hotel activities.
- 🛏️ **Room Management** - Add, update, search, and allocate rooms.
- 🧑‍💼 **Employee & Manager Management** - Maintain employee records.
- 📝 **Customer Handling** - Register new customers, assign rooms, and track their details.
- 📋 **Check-in/Check-out System** - Smooth handling of customer stays.
- 🚖 **Driver & Pick-up Services** - Manage transportation for guests.
- 🔍 **Search & Filter** - Find available rooms and employees quickly.
- 📊 **Data Storage** - Uses **MySQL database** to store and retrieve information.

## 🛠 Technologies Used
- **Java (Swing, AWT)** 🎨
- **MySQL Database** 🗄
- **JDBC (Java Database Connectivity)** 🔌
- **NetBeans / IntelliJ IDEA / VS Code** 💻

## 📂 Project Structure
```
📦 Hotel Management System
 ┣ 📜 HotelManagementSystem.java  # Main Entry Point
 ┣ 📜 Login.java  # User Authentication
 ┣ 📜 Dashboard.java  # Admin Dashboard
 ┣ 📜 Reception.java  # Front Desk Operations
 ┣ 📜 NewCustomer.java  # Register New Customers
 ┣ 📜 Room.java  # Room Information Display
 ┣ 📜 AddRoom.java  # Adding Rooms to the System
 ┣ 📜 SearchRoom.java  # Find Available Rooms
 ┣ 📜 UpdateCheck.java  # Modify Check-in Details
 ┣ 📜 CheckOut.java  # Check-out Process
 ┣ 📜 Employee.java  # Employee Database Management
 ┣ 📜 AddEmployee.java  # Adding New Employees
 ┣ 📜 ManagerInfo.java  # Manager Database
 ┣ 📜 Department.java  # Hotel Department Management
 ┣ 📜 CustomerInfo.java  # Customer Records
 ┣ 📜 PickUp.java  # Driver Pickup Services
 ┣ 📜 AddDrivers.java  # Adding New Drivers
 ┣ 📜 conn.java  # Database Connectivity (JDBC)
```

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/Hotel-Management-System.git
cd Hotel-Management-System
```

### 2️⃣ Configure the Database
- Install **MySQL** and create a database named `hms`.
- Import the provided SQL file (`hms.sql`) to set up tables.
- Update `conn.java` with your **database credentials**.

### 3️⃣ Compile & Run the Project
```sh
javac *.java
java HotelManagementSystem
```

## 📌 Future Enhancements
- 🌐 **Online Booking System** - Implement web-based reservations.
- 📱 **Mobile App** - Develop an Android/iOS version.
- 🧠 **AI-powered Customer Support** - Integrate chatbot assistance.

## 🤝 Contributing
Contributions are welcome! Feel free to **fork**, create a new branch, and submit a **pull request**.

## 📜 License
This project is licensed under the **MIT License**.

📧 **Contact:** [your-email@example.com]
