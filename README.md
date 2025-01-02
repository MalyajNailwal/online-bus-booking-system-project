# Online Bus Booking System

The Online Bus Booking System is a web application designed to streamline the process of reserving bus tickets. It simplifies booking for users and provides an easy-to-manage backend for administrators. The project uses modern web technologies to ensure a seamless and user-friendly experience.

## Features

### User Features
- **User Registration & Login**: Secure authentication system for users.
- **Bus Search**: Search buses by source, destination, and travel date.
- **Booking Management**: Book tickets, view bookings, and cancel reservations.
- **Payment Gateway Integration**: Easy and secure payment options.
- **Responsive Design**: Mobile-friendly interface for convenient use on any device.

### Admin Features
- **Dashboard**: View and manage bus schedules, routes, and bookings.
- **Bus Management**: Add, update, or remove buses and routes.
- **User Management**: Manage registered users and their bookings.
- **Reports**: Generate reports for sales, bookings, and user activities.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (Bootstrap for responsive design)
- **Backend**: PHP
- **Database**: MySQL
- **Others**: AJAX for dynamic content loading

## Requirements

- Web Server: Apache or Nginx
- PHP 7.x or higher
- MySQL 5.x or higher
- Composer (for dependency management)

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MalyajNailwal/online-bus-booking-system-project.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd online-bus-booking-system-project
   ```

3. **Set Up the Database**:
   - Create a database in MySQL.
   - Import the provided `database.sql` file into your MySQL database.

4. **Configure the Project**:
   - Update the database connection details in `config.php`:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "your_database_name";
     ```

5. **Deploy the Application**:
   - Place the project files in your web server's root directory.
   - Start the server and access the application through your browser.

6. **Admin Login**:
   - Default credentials:
     - Username: `admin`
     - Password: `admin123`
   - Update credentials after the first login for security.

## Usage

### User Guide
1. Register or log in to your account.
2. Search for buses by entering the source, destination, and date.
3. Select a bus and seat(s), then proceed to payment.
4. Confirm your booking and receive a ticket.
5. View and manage bookings from your dashboard.

### Admin Guide
1. Log in to the admin panel.
2. Use the dashboard to manage buses, routes, and bookings.
3. Generate reports to monitor activity.

## Screenshots
Include screenshots of the user and admin interfaces to showcase functionality.

## Contribution

We welcome contributions to enhance the Online Bus Booking System. Submit issues or pull requests on the [GitHub repository](https://github.com/MalyajNailwal/online-bus-booking-system-project).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

For any queries, feel free to contact [Malyaj Nailwal](mailto:malyajnailwal@example.com).
