# Employee-Management-Portal-EMP-
A full-featured web-based Employee Management System built using Java Server Pages (JSP), MySQL, and JDBC. This project enables Create, Read, Update, and Delete (CRUD) operations on employee records and provides a responsive user interface for seamless interaction. Ideal for students and developers learning Java EE and relational database integration.

 🚀 Features
🔍 **View Employees** – Display a list of all employees with their details  
➕ **Add Employee** – Add new employee records with salary, job title, etc.  
✏️ **Edit Employee** – Update existing employee information  
❌ **Delete Employee** – Remove employee records from the database  
💡 **Responsive UI** – Built with Bootstrap for a modern and mobile-friendly interface

🛠️ Technologies Used

- Java (JSP & Servlet)
- JDBC (Java Database Connectivity)
- MySQL
- Apache Tomcat
- HTML5, CSS3, Bootstrap 5

## 🧪 How to Run Locally

 1. Clone the Repository
git clone https://github.com/ys/employee-management-jsp.git

2. Create MySQL Database and Table
CREATE DATABASE helly;

USE helly;

CREATE TABLE empp1 (
    EmpNo INT PRIMARY KEY,
    EName VARCHAR(100),
    Job VARCHAR(100),
    Salary FLOAT
);

3. Configure Database Connection

Open DbConnect/Dbconnection.java and update the following:

String url = "jdbc:mysql://localhost:3306/helly";
String user = "your-username";
String password = "your-password";

4. Import Project and Deploy
Import project into Eclipse or NetBeans
Add Apache Tomcat Server
Clean, build, and run the project

5. Access the Web App
url
http://localhost:8080/YourProjectName/ViewEmp.jsp
📁 Project Structure
├── DbConnect/
│   └── Dbconnection.java
├── Web Pages/
│   ├── ViewEmp.jsp
│   ├── AddEmp.jsp
│   ├── EditEmp.jsp
│   ├── DeleteEmp.jsp
│   ├── updateemp.jsp
│   └── empform.jsp
