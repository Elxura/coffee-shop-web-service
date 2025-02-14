1. Introduction

- Opak Coffee is a web-based order and inventory management system designed to streamline product stock control, customer orders, and user administration. With the rapid growth of e-commerce and the increasing demand for efficient data management, Opak Coffee provides a seamless solution for real-time monitoring and automation of inventory and transactions.

2. Objectives

- Simplify stock and order management within a single integrated system.

- Optimize order processing and warehouse management for improved efficiency.

- Ensure secure access with robust user authentication features.

- Enhance transparency in inventory and transaction tracking.

3. Key Features

A. Warehouse Management (Stock Control)

- Add, Edit, and Delete Products: Admins can manage product details such as name, category, price, and stock availability.

- Stock Tracking: Real-time updates on initial stock, usage, and remaining stock.

- Recommendation Status: The system suggests restocking based on availability.

B. Order Management System

- Seamless Order Processing: Users can browse available products and place orders effortlessly.

- Dynamic Cart System: Allows quantity adjustment before order confirmation.

- Database Integration: Orders are logged in the order table, and warehouse stock is automatically updated.

C. User Authentication and Management

- Session-Based Login System: Ensures only authenticated users can access order and stock management features.

- Role-Based Access Control: Admins handle all functionalities, while customers can only browse and order.

- Password Recovery: Users can reset passwords via email using an SMTP service.

D. Dashboard and Reporting

- Stock and Sales Overview: Provides insights into stock levels and completed orders.

- Product Search and Filtering: Enables users to find products easily by category or name.

- Transaction History and Reports: Stores all order and stock update logs for tracking business performance.

4. Landing Page

- To enhance user engagement and system accessibility, Opak Coffee includes a professionally designed landing page.

A. Landing Page Features

- Hero Section: Displays a powerful tagline like "Manage Your Coffee Inventory Effortlessly!" with an aesthetic coffee-themed background.

- About Us: A brief introduction to Opak Coffee, its purpose, and how it helps streamline inventory and order management.

- Key Features Overview: Illustrated highlights of core functionalities, including:

- Real-Time Stock Monitoring

- Effortless Order Management

- Secure Authentication System

- Comprehensive Sales Reports

- How It Works: A step-by-step infographic guiding users on system usage from login to order fulfillment.

- Testimonials: User reviews and business success stories to build credibility.

- Call-to-Action (CTA):

Sign Up / Get Started: Directs users to register or log in.

Demo Request: Allows users to explore the system before full adoption.

Footer Section: Includes contact details, privacy policy, and social media links (if applicable).

5. Technologies Used

- Backend: PHP with MySQL database connectivity via koneksi.php.

- Database: MySQL tables including warehouse, order, keranjang, nota, and reset_password.

- Frontend: HTML, CSS (Bootstrap), JavaScript (jQuery or React for interactivity).

- Hosting & Deployment: Compatible with Apache/Nginx servers or cloud platforms like Azure, Netlify, or Vercel.

6. Installation Guide

- How to Install and Run the Project

- Download and Extract

- Download the Opak Coffee project files from the repository or source.

- Extract the files to the htdocs directory in your local XAMPP installation.

- Set Up Database

- Open phpMyAdmin via http://localhost/phpmyadmin/.

- Create a new database named opak_coffee.

- Import the provided SQL file (opak_coffee.sql) to initialize the database structure and sample data.

- Configure Database Connection

- Open the koneksi.php file.

- Update the database credentials (host, username, password, database) if necessary.

- Run the Project

- Start Apache and MySQL from the XAMPP control panel.

- Open a browser and navigate to http://localhost/opak_coffee/.

- Login and Use the System

- Use the provided admin credentials to log in and access the system's full functionality.

- Customers can register and place orders seamlessly.

7. Future Enhancements

- AI-Powered Stock Prediction: Analyzes order trends to recommend restocking levels.

- IoT-Based Real-Time Stock Monitoring: Integrates with sensors to track physical stock movements.

- Mobile Application: Expands accessibility for users on the go.

 - With its comprehensive features and modern technology stack, Opak Coffee is set to revolutionize inventory and order management, ensuring businesses run efficiently in the digital age.

