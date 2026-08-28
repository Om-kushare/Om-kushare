<h1 align="center">Hi 👋, I'm Om Kushare</h1>
<h3 align="center">A passionate frontend developer from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=om-kushare&label=Profile%20views&color=0e75b6&style=flat" alt="om-kushare" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=om-kushare" alt="om-kushare" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

- 🔭 I’m currently working on **Hotel Management**

- 🌱 I’m currently learning **java,html5,css3,sql**

- 📫 How to reach me **omkushare29@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/om kushare" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="om kushare" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=om-kushare&show_icons=true&locale=en&layout=compact" alt="om-kushare" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=om-kushare&show_icons=true&locale=en" alt="om-kushare" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=om-kushare&" alt="om-kushare" /></p>
# 🚚 Goods Transport Network

A web-based **Goods Transport Network Management System** developed using **Java, Spring MVC, Spring JDBC, MySQL, JSP, HTML, CSS, Bootstrap, and JavaScript**.

The system helps customers book vehicles according to their transportation requirements, while drivers can manage vehicles and transport requests. Administrators can manage customers, drivers, vehicles, and bookings from a centralized module.

---

## 📌 Project Overview

The **Goods Transport Network** is designed to simplify the process of managing goods transportation services.

The application provides separate role-based modules for:

* 👨‍💼 **Admin**
* 🚚 **Driver**
* 👤 **Customer**

The system manages customer bookings, driver assignments, vehicle information, and booking status through a centralized web application.

---

## 🎯 Objectives

* Provide an easy platform for customers to book transport vehicles.
* Allow drivers to register and manage their vehicles.
* Manage customer, driver, vehicle, and booking records.
* Provide booking status tracking.
* Reduce manual transportation management.
* Provide a responsive and user-friendly interface.

---

## 🛠️ Technologies Used

| Technology        | Purpose                         |
| ----------------- | ------------------------------- |
| ☕ Java            | Backend Development             |
| 🌱 Spring MVC     | Web Application Architecture    |
| 🔗 Spring JDBC    | Database Connectivity           |
| 🗄️ MySQL         | Database                        |
| 📄 JSP            | Dynamic Web Pages               |
| 🌐 HTML5          | Page Structure                  |
| 🎨 CSS3           | Styling                         |
| 🅱️ Bootstrap     | Responsive UI                   |
| ⚡ JavaScript      | Client-Side Functionality       |
| 📦 Maven          | Project & Dependency Management |
| 🖥️ Apache Tomcat | Application Server              |

---

## 🏗️ Architecture

The application follows a **Spring MVC layered architecture**.

```text
             ┌──────────────────────┐
             │       Customer       │
             │        Driver        │
             │        Admin         │
             └──────────┬───────────┘
                        │
                        ▼
             ┌──────────────────────┐
             │        JSP/UI        │
             │ HTML CSS Bootstrap   │
             │     JavaScript       │
             └──────────┬───────────┘
                        │
                        ▼
             ┌──────────────────────┐
             │      Controller      │
             │    Spring MVC        │
             └──────────┬───────────┘
                        │
                        ▼
             ┌──────────────────────┐
             │       Service        │
             │   Business Logic     │
             └──────────┬───────────┘
                        │
                        ▼
             ┌──────────────────────┐
             │    DAO / Repository  │
             │    Spring JDBC       │
             └──────────┬───────────┘
                        │
                        ▼
             ┌──────────────────────┐
             │        MySQL         │
             │      Database        │
             └──────────────────────┘
```

---

# 👥 Modules

## 👨‍💼 Admin Module

The Admin manages the complete transportation system.

### Features

* Admin Login
* Manage Customers
* Manage Drivers
* Manage Vehicles
* Manage Bookings
* View Booking Information
* Monitor System Records

---

## 🚚 Driver Module

The Driver module allows drivers to manage their vehicles and transportation requests.

### Features

* Driver Registration
* Driver Login
* Vehicle Registration
* View Assigned Booking Requests
* Manage Transport Requests
* View Booking History
* Update Vehicle Information

---

## 👤 Customer Module

The Customer module allows customers to book and track transportation services.

### Features

* Customer Registration
* Customer Login
* View Available Vehicles
* Book Vehicle
* View Booking Details
* Track Booking Status
* View Booking History

---

# 🔄 Booking Workflow

```text
Customer
   │
   ▼
Login / Registration
   │
   ▼
Enter Transportation Requirements
   │
   ▼
Select Available Vehicle
   │
   ▼
Create Booking
   │
   ▼
Booking Stored in MySQL
   │
   ▼
Driver Receives Request
   │
   ▼
Driver Manages Request
   │
   ▼
Booking Status Updated
   │
   ▼
Customer Tracks Booking
```

---

# 🗄️ Database

The application uses **MySQL** for storing and managing application data.

### Main Entities

```text
Admin
Customer
Driver
Vehicle
Booking
```

### Basic Relationship

```text
Customer
    │
    │ creates
    ▼
 Booking ─────────── Vehicle
    │
    │ assigned to
    ▼
 Driver
```

The database is used to store customer information, driver information, vehicle records, and booking details.

---

# ✨ Key Features

* 🔐 Role-based access
* 👤 Customer management
* 🚚 Driver management
* 🚛 Vehicle management
* 📦 Goods transportation booking
* 📋 Booking management
* 📊 Booking status tracking
* 🗄️ MySQL database integration
* 📱 Responsive user interface
* 🔄 CRUD operations
* 🏗️ MVC architecture

---

# 📂 Project Structure

```text
GoodsTransportNetwork
│
├── src
│   └── main
│       ├── java
│       │   └── com
│       │       └── ...
│       │
│       ├── resources
│       │
│       └── webapp
│           ├── WEB-INF
│           │   └── views
│           │       ├── admin
│           │       ├── customer
│           │       └── driver
│           │
│           ├── css
│           ├── js
│           └── images
│
├── pom.xml
└── README.md
```

> Update the package and folder names above according to your actual project structure.

---

# ⚙️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

## 2️⃣ Open the Project

Open the project in:

* Eclipse
* Spring Tool Suite (STS)
* IntelliJ IDEA

## 3️⃣ Configure MySQL

Create a MySQL database:

```sql
CREATE DATABASE gtn1;
```

Import your project database SQL file if available.

## 4️⃣ Configure Database Connection

Update the database configuration with your MySQL credentials:

```text
Database: gtn1
Username: your_username
Password: your_password
```

Do not commit real database passwords to GitHub.

## 5️⃣ Install Maven Dependencies

Run:

```bash
mvn clean install
```

## 6️⃣ Configure Tomcat

Deploy the application on **Apache Tomcat**.

## 7️⃣ Run the Application

Start Tomcat and open the application in your browser:

```text
http://localhost:8080/GoodsTransportNetwork/
```

> Replace `GoodsTransportNetwork` with your actual deployed context path.

---

# 🧪 Testing

The application can be tested using:

* Manual browser testing
* MySQL queries
* Postman for API testing where applicable
* JUnit for unit testing where implemented

---

# 🔒 Security Considerations

The application should protect sensitive information such as:

* User passwords
* Database credentials
* Authentication details

For production deployment, passwords should be securely hashed and database credentials should be stored using environment variables or secure configuration.

---

# 🚀 Future Enhancements

Possible improvements include:

* 🔐 Spring Security integration
* 🔑 Password encryption and authentication improvements
* 💳 Online payment integration
* 📍 Real-time vehicle tracking
* 📧 Email/SMS booking notifications
* 📱 Mobile application
* 🌐 REST API integration
* ☁️ Cloud deployment
* 📊 Advanced admin dashboard
* 🔔 Real-time booking notifications

---

# 📚 What I Learned

Through this project, I gained practical experience in:

* Java web application development
* Spring MVC architecture
* Spring JDBC
* MySQL database integration
* CRUD operations
* MVC-based application development
* Frontend and backend integration
* Role-based application design
* Debugging and problem solving
* Git and GitHub

---

# 👨‍💻 Developer

**Om Kushare**

🎓 Full Stack Java Developer

💻 Skills: Java | Spring MVC | Spring Boot | Spring JDBC | MySQL | HTML | CSS | JavaScript

📍 Pune, Maharashtra, India

---

## ⭐ If you Like This Project

If you find this project useful or interesting, consider giving the repository a ⭐.

---

## 📄 License

This project is developed for **educational and portfolio purposes**.

