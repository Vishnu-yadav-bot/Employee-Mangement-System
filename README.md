# Employee Management System

## 📝 Project Overview

The **Employee Management System** is a desktop-based Java application that allows an organization to manage employee records efficiently. It includes functionalities such as adding, updating, viewing, and removing employee data, as well as a secure login system. The application uses Java Swing for the graphical user interface and JDBC for database connectivity.

---

## 🚀 Features

* **Login System**: Secure login page to authenticate users.
* **Add Employee**: Input and store employee details in the database.
* **View Employees**: Retrieve and display all employees from the database.
* **Update Employee**: Modify details of existing employees.
* **Remove Employee**: Delete employee records.
* **Splash Screen**: Displays an animated splash screen on startup.
* **Modular Design**: Each feature is separated into modular Java classes.

---

## 📂 Project Structure

| File Name             | Description                                    |
| --------------------- | ---------------------------------------------- |
| `Splash.java`         | Displays splash screen with logo or animation. |
| `Login.java`          | Provides user login functionality.             |
| `AddEmployee.java`    | Allows admin to add a new employee.            |
| `View_Employee.java`  | Displays all employee records.                 |
| `UpdateEmployee.java` | Enables updating employee data.                |
| `RemoveEmployee.java` | Removes employee from the system.              |
| `conn.java`           | Handles database connection using JDBC.        |
| `Main_class.java`     | Main class to launch the application.          |

---

## 🛠️ Technologies Used

* **Java (Swing & AWT)** – For GUI components
* **JDBC (Java Database Connectivity)** – For database interaction
* **MySQL or Oracle DB** – Backend relational database (ensure JDBC URL is set accordingly)

---

## ⚙️ Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone <repo-url>
   ```

2. **Set up the database**:

   * Create a database named `ems` or as used in `conn.java`.
   * Create a table `employee` with relevant columns (id, name, age, position, etc.).

3. **Configure `conn.java`**:

   * Update your database URL, username, and password.

4. **Run the application**:

   * Compile and run `Main_class.java`.

---

## 📸 Screenshots (Optional)

You can include screenshots of the UI such as:

* Login screen
* Add/View/Update/Delete employee forms
* Splash screen animation

---

## 📌 Future Enhancements

* Password encryption and role-based access
* Export employee data to CSV or PDF
* Integration with cloud storage or web services

---

## 👨‍💻 Author

**G. Vishnu**
Sri Venkateshwara Engineering College, Tirupati
Email:gvishnuyadav3@gamil.com
LinkedIn: \[Add your LinkedIn URL]

