# 🚀 IntelliHire – Student Placement and Recruitment Management System

**IntelliHire** is a web-based Student Placement and Recruitment Management System developed using Java and MySQL. It helps students explore job opportunities, check placement eligibility, apply for jobs, and track their application status. It also enables administrators to manage companies, job postings, student records, and recruitment activities efficiently.

## 📌 Features

### 👨‍🎓 Student Module

* Student registration and login.
* Create and manage student profiles.
* Maintain academic details and skills.
* View available job opportunities.
* Check eligibility based on CGPA and backlogs.
* Apply for eligible job openings.
* Track job application status.

### 👨‍💼 Administrator Module

* Secure administrator login.
* Manage student records.
* Add and manage company details.
* Create, update, and delete job postings.
* Set job eligibility criteria.
* View student applications.
* Update recruitment and selection statuses.
* Generate placement reports.

## 🛠️ Technologies Used

| Technology    | Purpose                                |
| ------------- | -------------------------------------- |
| Java          | Backend development                    |
| Java Servlets | Request handling and application logic |
| JSP           | Dynamic web pages                      |
| JDBC          | Java–MySQL connectivity                |
| MySQL         | Database management                    |
| HTML5         | Web page structure                     |
| CSS3          | Styling and responsive layouts         |
| JavaScript    | Client-side interactivity              |
| Apache Tomcat | Web application server                 |
| NetBeans IDE  | Development environment                |

## 🏗️ System Architecture

```text
                 IntelliHire
                      |
                      v
            HTML / CSS / JavaScript
                      |
                      v
                 JSP Pages
                      |
                      v
                Java Servlets
                      |
                      v
                     JDBC
                      |
                      v
                    MySQL
```

## 🗄️ Database Structure

The application uses MySQL to store and manage information.

| Table          | Description                                              |
| -------------- | -------------------------------------------------------- |
| `users`        | Stores login credentials and user roles                  |
| `students`     | Stores student profiles and academic details             |
| `companies`    | Stores company information                               |
| `jobs`         | Stores job descriptions and eligibility criteria         |
| `applications` | Stores student job applications and application statuses |

## ⚙️ Installation and Setup

### Prerequisites

Install the following software before running the project:

* Java Development Kit (JDK)
* NetBeans IDE
* Apache Tomcat
* MySQL Server
* MySQL Connector/J

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/IntelliHire-Placement-Management-System.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Open the Project

1. Open NetBeans IDE.
2. Select **File → Open Project**.
3. Choose the cloned project folder.
4. Configure Apache Tomcat as the application server if required.

### Step 3: Configure MySQL

1. Start your MySQL server.
2. Create the project database.
3. Execute the SQL script provided in the project.
4. Configure the database connection details in the application's database connection class.

Example database creation:

```sql
CREATE DATABASE intellihire;
```

Update the JDBC connection settings according to your local MySQL configuration.

### Step 4: Configure JDBC

Add MySQL Connector/J to the project's libraries and configure the JDBC connection.

Example connection URL:

```java
String url = "jdbc:mysql://localhost:3306/intellihire";
```

Configure the database username and password securely. Do not commit real credentials to GitHub.

### Step 5: Run the Application

1. Right-click the project in NetBeans.
2. Select **Clean and Build**.
3. Select **Run**.
4. Open the application using the URL provided by Tomcat.

**Note:** The exact setup steps may vary depending on the project structure and Tomcat configuration.

## 🔐 Security Considerations

* Use prepared statements to help prevent SQL injection.
* Store passwords using a secure password-hashing method.
* Validate user input on the server.
* Restrict administrator functions to authorized users.
* Keep database credentials outside publicly committed source files.
* Validate uploaded resume files and restrict their size and file types.

## 🔮 Future Enhancements

* AI-powered resume analysis.
* Skill-based job recommendations.
* Email notifications for application updates.
* Online aptitude tests and coding assessments.
* Interview scheduling and reminders.
* Interactive placement statistics dashboard.
* Resume–job description matching.
* Exportable placement reports.

## 🎯 Project Objectives

* Simplify campus placement activities.
* Provide students with a centralized job application platform.
* Automate eligibility verification.
* Improve recruitment data management.
* Reduce manual work for placement administrators.

## 👨‍💻 Author

Pavani Thulasi Swarna


## 📄 License

This project is intended for educational and portfolio purposes. Add a license file if you wish to specify the terms under which others may use, modify, or distribute the code.

---

⭐ If you find this project useful, consider giving the repository a star!
