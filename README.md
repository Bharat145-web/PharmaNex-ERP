# PharmaNex-ERP
**PharmaNex ERP** is a database-driven system designed to streamline pharmaceutical operations. It manages inventory, sales, purchases, employees, and finance through a centralized database, ensuring data accuracy, faster processing, and real-time insights for efficient business management.


PharmaNex ERP is a database-driven Enterprise Resource Planning (ERP) system designed specifically for pharmaceutical companies and medical distributors. The project aims to streamline various business operations such as inventory control, sales management, supplier coordination, employee management, and customer handling through a centralized database system.

This DBMS project focuses on building a relational database that ensures data consistency, integrity, and accessibility across multiple modules of the ERP. It helps automate day-to-day processes, minimizes manual errors, and provides analytical insights for better decision-making in the pharmaceutical domain.

Objectives:

To design and implement a normalized database schema for managing pharmaceutical operations.

To integrate various business functions like procurement, inventory, sales, and finance in a unified system.

To maintain accurate stock levels and track medicine batches, expiry dates, and suppliers.

To generate real-time reports for management decisions.

To ensure data security and role-based access control for different system users.

Key Modules:

Inventory Management:

Tracks medicines, raw materials, and packaging items.

Maintains stock levels, batch numbers, expiry dates, and reorder points.

Sales & Distribution:

Handles customer orders, invoices, and delivery records.

Tracks sales performance and generates billing reports.

Purchase & Supplier Management:

Manages supplier details, purchase orders, and payment records.

Automates restocking based on inventory thresholds.

Employee Management:

Stores employee data, roles, and attendance.

Assigns permissions based on user roles (Admin, Pharmacist, Salesperson, etc.).

Finance Module:

Records transactions, billing, and payment histories.

Generates profit/loss and expense reports.

Customer Management:

Maintains customer details and purchase histories.

Provides data for CRM and marketing analytics.

Database Design:

Entities: Medicine, Supplier, Customer, Employee, Purchase, Sales, Inventory, Payment, User.

Relationships:

One supplier → many medicines

One customer → many sales

One purchase → many items

One employee → many transactions

Normalization: Achieved up to 3NF to avoid redundancy and maintain consistency.

Database Used: MySQL / Oracle / PostgreSQL (depending on your setup).

Technologies Used:

Frontend: HTML, CSS, JavaScript / PHP / Java / Python (based on your implementation)

Backend: MySQL / Oracle Database

Tools: XAMPP / MySQL Workbench / SQL Developer

Languages: SQL, PL/SQL



<h1 align="center" id="title">PHARMAnexERP</h1>

<div align="center">
 <img src="./Preview/Screenshot 2024-10-10 at 1.02.21 PM.png" alt="Image" style="width: 80%;"/>
 <br>Homepage<br><br>
 <hr>
 <img src="./Preview/Screenshot 2024-10-10 at 1.02.40 PM.png" alt="Image" style="width: 80%;"/>
 <br>Products Page<br><br>
 <hr>
 <img src="./Preview/Screenshot 2024-10-10 at 1.03.00 PM.png" alt="Image" style="width: 80%;"/>
 <br>Admin Dashboard<br><br>
 <hr>
 <img src="./Preview/Screenshot 2024-10-10 at 1.03.12 PM.png" alt="Image" style="width: 80%;"/>
 <br>Contact Us page<br><br>
 <hr>
</div>

## Colour Palette

**Headings** = #111111 <br>
**Content** = #444444 <br>
**Buttons** = #0098DA

## User Logins

### Admin Login

**Username**: admin01
**Password**: mod123

### Manager Login

**Username**: manager01
**Password**: managerPass02

**Username**: manager02
**Password**: managerPass03

### Customer Login

**Username**: user01
**Password**: userPass01

**Username**: user02
**Password**: userPass02


