# Student Information System

A comprehensive, full-stack web application for managing student records within an educational institution. Built with PHP and MySQL, it provides a secure and intuitive interface for performing essential CRUD (Create, Read, Update) operations.

<img width="1862" height="957" alt="index page " src="https://github.com/user-attachments/assets/cdee65e1-7e6b-4f96-a2fc-399bc187bf6c" />


## 🚀 Features

- **Dashboard Overview:** View all student records in a clean, sortable table.
- **Add New Students:** Intuitive form to input student details (Name, Email, Age, Course).
- **Update Records:** Edit existing student information with pre-populated forms.
- **Real-Time Search:** Dynamically filter students by name or email directly from the main page.
- **Responsive Design:** Fully compatible with desktop, tablet, and mobile devices thanks to Bootstrap 5.
- **User Feedback:** Interactive toast notifications for successful actions or errors.
- **Secure:** Implements prepared statements to prevent SQL injection attacks.

## 🛠️ Built With

*   **Frontend:**
    *   HTML5
    *   CSS3
    *   JavaScript (Vanilla)
    *   [Bootstrap 5](https://getbootstrap.com/) - Frontend CSS framework
*   **Backend:**
    *   [PHP](https://www.php.net/) - Server-side scripting language
*   **Database:**
    *   [MySQL](https://www.mysql.com/) - Relational database management system
*   **Server:**
    *   XAMPP/WAMP (for local development)

## 📦 Installation & Setup

Follow these steps to set up the project locally on your machine.

1.  **Prerequisites:**
    *   Ensure you have a web server stack installed (e.g., [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/)).

2.  **Clone the Repository:**
    ```bash
    git clone https://github.com/YeshwanthRajSelvaraj/Student-Information-Management-System.git
    ```
    Move the cloned folder to your server's root directory (e.g., `xampp/htdocs/`).

3.  **Database Setup:**
    *   Open your PHPMyAdmin panel (usually at `http://localhost/phpmyadmin`).
    *   Create a new database named `student_info`.
    *   Import the provided SQL schema from `SQL DB Dump.txt` into your new database.

4.  **Configuration:**
    *   Open the `config.php` file.
    *   Update the database credentials if your local MySQL setup differs from the default.
    ```php
    $servername = "localhost";
    $username = "root"; // Your MySQL username
    $password = ""; // Your MySQL password
    $dbname = "student_info";
    ```

5.  **Run the Application:**
    *   Start your Apache and MySQL modules via XAMPP/WAMP.
    *   Open your browser and navigate to: `http://localhost/Student-Information-Management-System/index.php`

## 📖 Usage

1.  **Viewing Records:** The homepage (`index.php`) displays all existing student records.
2.  **Adding a Student:** Click the "Add New Student" button to navigate to the form, fill in the details, and submit.
3.  **Searching:** Use the search box at the top of the table to filter students in real-time.
4.  **Editing a Student:** Click the "Edit" button next to any student record to modify their information.

## 🗄️ Database Schema

The application uses a single table:

**Table: `students`**
| Column | Type | Attributes |
| :--- | :--- | :--- |
| `id` | INT | PRIMARY KEY, AUTO_INCREMENT |
| `name` | VARCHAR(100) | NOT NULL |
| `email` | VARCHAR(100) | NOT NULL |
| `age` | INT | NULL |
| `course` | VARCHAR(100) | NULL |

## 🔮 Future Enhancements

*   Implement **Delete** functionality to complete the CRUD cycle.
*   Add user authentication and role-based access control (Admin, User).
*   Introduce data pagination for better performance with large datasets.
*   Add data validation for email uniqueness and age input.
*   Export data to CSV/PDF functionality.

## 👨‍💻 Developer

- **Your Name** - [LinkedIn Profile Link](https://www.linkedin.com/in/yeshwanth-raj-selvaraj-153796248/) - [GitHub Profile Link](https://github.com/YeshwanthRajSelvaraj)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**⭐ Star this repo if you found it helpful!**
