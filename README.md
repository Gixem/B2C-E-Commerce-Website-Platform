# 🛒 B2C E-Commerce Platform

A robust, scalable, and feature-rich **B2C (Business-to-Consumer) E-Commerce Platform** built using **ASP.NET Core MVC**. 
This project demonstrates a clean implementation of essential e-commerce functionalities, including dynamic cart management, advanced coupon logic, and administrative content control.

## 🏗 System Architecture & Technologies

* **Framework:** .NET 6.0/7.0 (ASP.NET Core MVC) 
* **Database:** MS SQL Server (Schema managed via T-SQL scripts)
* **IDE:** Developed using Visual Studio 2022 
* **Architecture:** Model-View-Controller (MVC) pattern for clean separation of concerns

## 🚀 Key Features

### Shopping & Cart Management
* **Dynamic Cart Tracking:** Real-time monitoring of item counts and totals during the shopping session.
* **Optimized Checkout Flow:** A structured process from customer info collection to order completion.
* **Order Summaries:** Detailed breakdown of items before final purchase confirmation.

### Marketing & Promotions
* **Coupon Management System:** An integrated module for listing, adding, and validating discount coupons to enhance user retention.

### Administrative Controls
* **Content Management (CMS):** Full operations for product categories, allowing administrators to manage the store catalog efficiently.
* **Secure Deletion:** Safe handling of category removals and data management.
* **Automated Schema Deployment:** Ready-to-use SQL scripts for quick database environment setup.

## 🛠 Setup & Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/B2C-Ecommerce-Platform.git](https://github.com/your-username/B2C-Ecommerce-Platform.git)
    ```
2.  **Database Configuration:**
    * Open MS SQL Server Management Studio (SSMS).
    * Execute the provided `script.sql` file to initialize the database.
    * Update the `ConnectionStrings` in your local configuration.
3.  **Run the Application:**
    * Open the solution in Visual Studio 2022[cite: 1].
    * Press `F5` or use the command `dotnet run`.
