# Vehicle-Management-System
This repository contains the Vehicle Management System project, a web-based application for managing and tracking vehicles. The system allows users to register new vehicles, update vehicle information, delete vehicles, and generate reports. The application is developed using PHP and MySQL, providing an efficient and user-friendly interface for managing vehicles. This README provides an overview of the project and instructions for setting it up and running the application.

# Features
The Vehicle Management System offers the following key features:

1. Vehicle Registration: Register new vehicles by providing details such as make, model, year, color, and registration number.
2. Vehicle Update: Update the information of existing vehicles, including their status, mileage, and any additional details.
3. Vehicle Deletion: Remove vehicles from the system when they are no longer in use or have been sold.
4. Search and Filtering: Perform searches and apply filters to find specific vehicles based on various attributes, such as make, model, or registration number.
5. Reporting: Generate reports and summaries of vehicles based on different criteria, such as total count, available vehicles, or vehicles by make and model.

# Technologies Used

* Backend: PHP (7.x or later)
* Database: MySQL (5.x or later)
* Frontend: HTML, CSS, JavaScript
* Web Server: Xampp( Apache, phpmyadmin)

# Setup
To set up the Vehicle Management System project, follow the steps below:

1. Clone the repository to your local machine:
   git clone https://github.com/riyamehta02/vehicle-management-system.git
2. Set up a web server environment (Apache or Nginx) and configure it to serve the project directory as the document root.
3. Import the database schema:
   * Create a new database in your MySQL server.
   * Import the database schema from the database.sql file provided in the project directory.
4. Update the database configuration:
   * Open the 'config.php' file in the project directory.
   * Update the 'DB_HOST', 'DB_NAME', 'DB_USER', and 'DB_PASSWORD' constants with your MySQL server details.
5. Start Your Web server.
6. Access the application by visiting the appropriate URL in your web browser.
