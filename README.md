# Travixo - Tours & Travel Management System

## Overview
Travixo is a comprehensive web-based Tours and Travel Management System built with PHP and MySQL. This project is designed to help travel agencies manage their tour packages, handle customer bookings, and streamline their administrative operations. 

## Features
- **User Authentication**: Secure login and registration for customers and administrators.
- **Tour Packages**: Browse and view detailed itineraries of various travel packages.
- **Booking System**: Users can book tour packages and check availability.
- **User Dashboard**: Customers can manage their profiles, view booking history, and submit inquiries.
- **Admin Panel**: A dedicated administrative dashboard to manage users, packages, bookings, and issues/tickets.
- **Responsive Design**: User-friendly interface accessible on both desktop and mobile devices.

## Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Setup Instructions

To run this project locally, follow these steps:

1. **Install a Local Web Server**: Download and install XAMPP, WAMP, or any similar software.
2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/travixo.git
   ```
3. **Move to Root Directory**: Place the `Travixo` folder inside your local server's root directory:
   - For XAMPP: `C:\xampp\htdocs\`
   - For WAMP: `C:\wamp\www\`
4. **Database Configuration**:
   - Open PHPMyAdmin (usually `http://localhost/phpmyadmin`).
   - Create a new database named `tms` (or check the exact name inside the `database` folder).
   - Import the provided SQL file located in the `database/` folder into your newly created database.
5. **Database Connection**: If needed, update the database connection settings in the `includes/config.php` file to match your local database credentials (username: `root`, password: `""` by default on XAMPP).
6. **Run the Project**: Open your web browser and navigate to `http://localhost/Travixo/index.php`.



## Contact
Developed by Hitesh Limbachiya.
