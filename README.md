# CITY-TAXI-SERVICE
The CITY-TAXI-SERVICE is a comprehensive web application designed to manage taxi services efficiently. This platform provides a seamless experience for passengers, drivers, and operators, integrating various functionalities to ensure smooth operations and user satisfaction. CITY-TAXI-SERVICE offers a full-featured admin panel for managing drivers, passengers, and trips. The system includes user authentication, profile management, trip reservations, and feedback collection. The admin can monitor service logs, track payments, and ensure the quality of service through an intuitive dashboard.

## Features

- **Admin Panel:**
  - Manage drivers, passengers, and services.
  - Monitor service logs and trip history.
  - View and manage feedback from drivers and passengers.
  - Track payments and view payment history.
  
- **Driver Management:**
  - Profile management and status updates.
  - View and manage service logs.
  
- **Passenger Management:**
  - Profile management and trip history.
  - Reserve trips and select drivers.
  - Provide feedback on the service.

- **Authentication:**
  - Secure login and logout for all user roles.
  - Profile editing and status management.

- **Feedback System:**
  - Collect and manage feedback from drivers and passengers.

- **Payment Tracking:**
  - Track and view payment history.

## Installation

### Prerequisites

- **XAMPP or WAMP Server:** To run the PHP application locally.
- **MySQL Database:** For managing the application's data.
- **Composer:** For managing dependencies.

### Steps

1. **Clone the repository:**
   ```bash
   git clone git@github.com:YourUsername/CITY-TAXI-SERVICE.git

2. **Set up the database**:

  - Import the SQL files located in the `DB` directory (`db_city_taxi.sql` and `table_admin_panel.sql`) into your MySQL server.

3. **Install dependencies**:

  - Navigate to the project directory and run:
    ```bash
    composer install
    npm install

4. **Configure the application**:

  - Update the database connection details in the `includes` directory.

5. **Run the application**:

  - Start your local server (XAMPP or WAMP).
  - Navigate to the project directory and access the application via `http://localhost/city-taxi-service`.

## Contribution

We welcome contributions to enhance the CITY-TAXI-SERVICE project. To contribute:

  1. Fork the repository.
  2. Create a new branch (`git checkout -b feature/your-feature-name`).
  3. Commit your changes (`git commit -m 'Add some feature`').
  4. Push to the branch (`git push origin feature/your-feature-name`).
  5. Open a Pull Request.
  
Please make sure your code follows our coding guidelines and is well documented.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
  ```bash
  You can save this content into a file named `README.md` in your project directory.
