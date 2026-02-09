🏨 Hotel Management System (Java + MySQL)

A desktop-based Hotel Management System developed using Java (Swing & AWT) and MySQL.
This application helps in automating day-to-day hotel operations such as customer management, room allocation, employee handling, pickup services, and billing.

The project is designed with a clean GUI, efficient database connectivity, and modular structure, making it ideal for college mini/major projects and resume showcase.

🚀 Features
🔐 Authentication

Secure Admin Login

Controlled access to hotel operations

🛎️ Customer & Room Management

New customer registration with ID verification

Room allocation during check-in

Real-time room availability tracking

Checkout with automatic timestamp generation

Update room and customer status

👨‍💼 Employee Management

Add and manage employee details

Track job role, salary, contact number, and Aadhaar

View complete employee information

🚗 Pickup & Driver Services

Add drivers with vehicle details

Pickup service based on car type and availability

Location-based service assignment

🧑‍💻 Administration

Department-wise budget overview

Manager and customer information panels

Room search with filters (bed type, availability)

| Technology   | Usage                   |
| ------------ | ----------------------- |
| Java         | Core application logic  |
| Swing & AWT  | GUI development         |
| MySQL        | Database                |
| JDBC         | Database connectivity   |
| NetBeans IDE | Development environment |


Hotel-Management-System/
│
├── hotel.management/
│   ├── Login.java
│   ├── Dashboard.java
│   ├── AddCustomer.java
│   ├── AddRooms.java
│   ├── AddEmployee.java
│   ├── AddDriver.java
│   ├── SearchRoom.java
│   ├── Pickup.java
│   ├── UpdateCheck.java
│   ├── Checkout.java
│   ├── CustomerInfo.java
│   ├── ManagerInfo.java
│   ├── Department.java
│   └── Conn.java
│
├── icons/
├── screenshots/
├── libraries/
│   ├── mysql-connector-java-8.0.28.jar
│   ├── rs2xml.jar
│   └── jcalendar.jar
│
└── README.md

⚙️ Installation & Setup

1️⃣ Prerequisites

JDK 21 or compatible

MySQL Server

Apache NetBeans IDE

2️⃣ Database Configuration

Create a MySQL database (example: hotelmanagementsystem)

Create required tables

Update database credentials in Conn.java

DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/hotelmanagementsystem",
    "username",
    "password"
);

3️⃣ Run the Application

Open the project in Apache NetBeans IDE

Add required .jar libraries:

mysql-connector-java

rs2xml

jcalendar

Run Login.java to start the application

🎯 Use Cases

This project is ideal for:

College Mini / Major Projects

Java + SQL resume projects

Learning Java Swing GUI development

Understanding JDBC & MySQL integration

🔮 Future Enhancements

Role-based login (Admin / Receptionist)

Bill & invoice PDF generation

Online room booking module

Improved input validation & security

Migration to JavaFX or web-based UI

👨‍💻 Author

Ayush Seth
Computer Science & Engineering
Java | SQL | Desktop Applications

📌 About

A desktop-based Hotel Management System built using Java (Swing & AWT) and MySQL to efficiently manage hotel operations including room allocation, customer check-in/check-out, employee management, and pickup services.
