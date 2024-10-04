# Visa Processing System

An efficient, automated solution for managing visa applications, processing, and tracking. The **Visa Processing System** accelerates the visa application process by allowing users to apply for and track their visa status online, while securely storing the information for future reference. It supports both **Tourist** and **Student** visas.

## Features:

- **Submit Visa Applications**: Users can submit their personal and visa details via an easy-to-use form.
- **Track Visa Application Status**: Users can track the status of their visa application in real time.
- **Application and Payment History**: Provides a record of visa applications and payment history for users.
- **Role-Based Access**: Admin and user roles are supported, where admins can manage applications and users can submit and track their own applications.
- **Data Security**: Sensitive data is securely stored and encrypted using Java Spring's security features.
- **Database Support**: Uses **MySQL** for storing user and visa-related data.
- **Spring Framework**: Built with **Java Spring** for efficient backend processing.

## Tech Stack:

- **Java** (Core Java)
- **Spring Boot** (Backend)
- **MySQL** (Database)
- **JDBC** (Database connection)
- **HTML, CSS, JavaScript** (Front-end)

---

## 🚀 Installation and Setup

Follow these steps to set up the **Visa Processing System** on your local machine:

1. **Clone the repository** to your local machine using Git:

   ```bash
   git clone https://github.com/Siddharthprabhakar/visa-processing-system.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd visa-processing-system
   ```

3. **Set up the MySQL Database**:
   - Create a MySQL database (e.g., `visa_db`).
   - Use the `visa_jdbc.sql` script provided in the `resources` folder to create the necessary tables and seed some initial data.

4. **Configure application properties**:
   - In the `application.properties` file located in `src/main/resources/`, update the MySQL database credentials:

     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/visa_db
     spring.datasource.username=your_mysql_username
     spring.datasource.password=your_mysql_password
     ```

5. **Build and run the application**:

   - Using Maven, build the project and package it:

     ```bash
     mvn clean install
     ```

   - Run the application:

     ```bash
     java -jar target/visa-processing-system.jar
     ```

6. **Access the Application**:
   - You should see the application's login screen.

   - **Admin Login Credentials**:
     - Email: `admin@admin.com`
     - Password: `admin123`

---

## 🤝 Contributing

We welcome contributions to improve the Visa Processing System! Here's how you can help:

- **Bug Reports**: If you find a bug, please open an issue in the GitHub repository.
- **Feature Requests**: If you have a suggestion or feature request, feel free to submit an issue describing the enhancement.
- **Pull Requests**: We welcome pull requests! If you have a feature or bug fix, feel free to submit a pull request with a detailed description of your changes.

---

## 📧 Contact

If you have any questions or need support, feel free to contact me at:
- Email: sid130803@gmail.com
- [LinkedIn](https://www.linkedin.com/in/siddharth1308/)

---
