# Apparel Production and Inventory Management System

**Project ID:** ISP_G28  
**Module:** IE2091 - Information Systems Project (2026)  
**Institution:** Sri Lanka Institute of Information Technology (SLIIT)

---

## 📋 Project Overview

Dinusha Embroidery, a baby garments manufacturing factory, previously relied on manual Excel-based processes. This caused data inaccuracies, production delays, payroll errors, poor inventory visibility, and critical safety risks — especially with broken and missing needles, which affect export compliance.

The **Apparel Production and Inventory Management System** is a **web-based integrated solution** developed to automate and digitize the factory’s core operations. The system provides real-time visibility, role-based access control, and strong safety compliance.

**Key Innovation:** The **Common Target Dashboard** — visible to all users for daily sewing targets, while only the Production Manager can update it.

---

## ✨ Core Features

- **Production Planning** — Create, view (Daily/Weekly/Monthly), and manage production plans with machine assignment
- **Payroll Management** — Employee registration and automated salary calculation (Basic + OT + Allowances - Advances)
- **Needle Management** — Record broken/missing/normal needles, manage needle types, prevent duplicates, and send critical alerts
- **Inventory Management** — Track stock levels, low-stock alerts, and updates
- **Support Tickets** — Raise and resolve internal support issues
- **Reports & Analytics** — Comprehensive reporting and dashboards
- **Audit Logging** — Track important system actions for accountability

---

## 🛠️ Technology Stack

- **Backend**: Spring Boot (Java)
- **Frontend**: Thymeleaf + HTML/CSS/JavaScript
- **Database**: MySQL
- **Security**: Spring Security + JWT + BCrypt
- **Build Tool**: Maven
- **Architecture**: MVC with Role-Based Access Control (RBAC)

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Thenulaperera/Apparel-Production-and-Inventory-Management-System-.git

 2. Database Setup (Important)

Install and run XAMPP (or any MySQL server)
Open phpMyAdmin (http://localhost/phpmyadmin)
Create a new database named pim_system
(Optional) Import the provided SQL dump if available, otherwise the system will auto-create tables on first run.

3. Configure Application
Open src/main/resources/application.properties and ensure the following:
propertiesspring.datasource.url=jdbc:mysql://localhost:3306/pim_system?createDatabaseIfNotExist=true&useSSL=false&serverTimezone=UTC&allowPublicKeyRetrieval=true
spring.datasource.username=root
spring.datasource.password=
4. Run the Application

Open the project in IntelliJ IDEA
Run PimSystemApplication.java as a Spring Boot application

5. Access the System
Open your browser and go to:
http://localhost:8080
Demo Credentials:

Admin: admin@example.com / admin123
Employee: employee@example.com / employee123


📸 Screenshots
(Add screenshots here)
Admin: admin@example.com / admin123
Employee: employee@example.com / employee123



