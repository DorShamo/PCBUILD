# 💻 Bistro: Restaurant Management System

### 🖥️ Project Overview

Bistro is a comprehensive backend-focused restaurant management system developed as a core project during my second year of Software Engineering studies. The application streamlines restaurant operations by managing table reservations, tracking menu items, and handling customer orders through a robust relational database structure. It emphasizes clean separation of concerns using a Model-View-Controller (MVC) architecture.

---

### 🛠️ Technologies Used

* **Java:** Used for core business logic, controller implementation, and data processing.
* **MySQL:** Managed the relational database schema, including tables for reservations, menu items, and order history.
* **SQL (JDBC):** Facilitated secure communication between the Java application and the database.
* **UML:** Employed for system design, including class diagrams and sequence diagrams to map out the application flow.
* **Git:** Version control used to track development progress and collaboration.

---

### 🚀 Key Features

* **Reservation Management:** A dedicated `Reservation_Controller` handles booking requests, checking for table availability, and managing time slots.
* **Dynamic Menu Handling:** Ability to add, update, or remove menu items from the database in real-time.
* **Order Tracking:** Logic to link customer orders to specific tables and track the status of items prepared in the kitchen.
* **Data Integrity:** Implemented SQL constraints and Java validation logic to ensure consistent data across all entities.
* **Scalable Architecture:** Designed with modularity in mind, allowing for future expansion such as adding staff management or payment integration.

---

### 🏗️ System Architecture

The project follows a standard 3-tier architecture, ensuring that the presentation layer is decoupled from the data management layer. The `Reservation_Controller` acts as the intermediary, processing user inputs and executing the necessary SQL queries to update the state of the restaurant.

---

### 📂 Project Structure

```text
/Bistro-Project
├── /src/controllers    # Logic for reservations and order management
├── /src/models         # Database entities (Menu, Table, Order)
├── /sql                # Database schema and initial data scripts
├── /docs               # UML diagrams and project documentation
└── README.md
