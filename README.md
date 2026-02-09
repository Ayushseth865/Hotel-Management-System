Hotel Management System (Java + MySQL)
A desktop-based Hotel Management System developed using Java (Swing & AWT) and MySQL, aimed at automating and managing day-to-day hotel operations such as customer handling, room allocation, employee management, pickup services, and billing.

The system provides a clean graphical interface, efficient database integration, and modular design, making it suitable for academic projects and real-world use cases.

Key Features
Authentication
Secure Admin Login
Controlled access to hotel operations
Customer & Room Management
New customer registration with ID verification
Room assignment during check-in
Real-time room availability tracking
Checkout with automatic timestamp generation
Update room and customer status
Employee Management
Add and manage employee details
Job role, salary, contact, and Aadhaar tracking
View all employee information
Pickup & Driver Services
Add drivers with vehicle details
Pickup service based on car type and availability
Location-based service assignment
Administration
Department-wise budget overview
Manager and customer information panels
Search rooms using filters (bed type, availability)
Screenshots
Splash / Welcome Screen
Screenshot 2026-01-22 113547 Screenshot 2026-01-22 113649
Login Screen
Screenshot 2026-01-22 113606
Admin Dashboard
Screenshot 2026-01-22 113709
New Customer Form
Screenshot 2026-01-22 113734
Add Rooms
Screenshot 2026-01-22 114036
Add Employee
Screenshot 2026-01-22 114020
Add Driver
Screenshot 2026-01-22 114056
Search Room
Screenshot 2026-01-22 113942
Pickup Service
Screenshot 2026-01-22 113923
Update Check-in Status
Screenshot 2026-01-22 113851
Checkout
Screenshot 2026-01-22 113831
Department Budget
budget
Tech Stack
Technology	Usage
Java	Core application logic
Swing & AWT	GUI development
MySQL	Database
JDBC	Database connectivity
NetBeans IDE	Development environment
📁 Project Structure
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
│
├── screenshots/
│   ├── splash.png
│   ├── login.png
│   ├── dashboard.png
│   ├── new_customer.png
│   ├── add_rooms.png
│   ├── add_employee.png
│   ├── add_driver.png
│   ├── search_room.png
│   ├── pickup_service.png
│   ├── update_status.png
│   ├── checkout.png
│   ├── department.png
│   ├── customer_info.png
│   ├── manager_info.png
│   └── reception.png
│
├── libraries/
│   ├── mysql-connector-java-8.0.28.jar
│   ├── rs2xml.jar
│   └── jcalendar.jar
│
└── README.md
Installation & Setup
1️. Prerequisites
JDK 21 or compatible
MySQL Server
Apache NetBeans IDE
2️. Database Configuration
Create a MySQL database (example: hotelmanagementsystem)
Create required tables
Update database credentials in Conn.java
DriverManager.getConnection(
  "jdbc:mysql://localhost:3306/hotelmanagementsystem",
  "username",
  "password"
);
Run the Application
Open the project in Apache NetBeans IDE
Add the required .jar libraries:
mysql-connector-java
rs2xml
jcalendar
Run the Login.java file to start the application
Project Use Case
This project is suitable for:

College Mini / Major Projects
Java + SQL based resume projects
Learning Java Swing GUI development
Understanding JDBC & MySQL database integration
Future Enhancements
Role-based login (Admin / Receptionist)
Bill & invoice PDF generation
Online room booking module
Improved input validation and security
Migration to JavaFX or web-based UI
Author
Ayush Seth
Computer Science & Engineering
Java | SQL | Desktop Applications
