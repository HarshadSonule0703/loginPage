# loginPage

# 🔐 Login Page Project using Advanced Java (JDBC, Servlet, JSP)

## 📌 Project Overview

This project is a simple yet functional **Login and Registration Page** system built using **Advanced Java technologies** including **Servlets, JSP, JDBC**, and **MySQL** as the backend database. The application allows users to register an account and log in securely.

---

## 🛠️ Technologies Used

- **Java (Servlet, JSP)**
- **JDBC**
- **SQL**
- **HTML5 & CSS3**
- **Bootstrap (for styling)**

---

## 📂 Project Structure
LoginProject/
├── src/
│ ├── com.project.controller/
│ │ ├── LoginServlet.java
│ │ └── RegisterServlet.java
│ └── com.project.util/
│ └── DBConnection.java
├── WebContent/
│ ├── login.jsp
│ ├── register.jsp
│ └── welcome.jsp
├── lib/
│ └── mysql-connector-java.jar
├── .classpath
├── .project
└── README.md


---

## 📊 Database Details

- **Database Name:** `Oracle`
- **Table Name:** `users001`

**Table Structure:**

| Column Name | Data Type |
|-------------|-----------|
| uname       | VARCHAR2 (PK)  |
| pword       | VARCHAR2  |
| fname       | VARCHAR2  |
| lname       | VARCHAR2  |
| city        | VARCHAR2  |
| mid         | VARCHAR   |
| phno        | NUMBER    |

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   https://github.com/HarshadSonule0703/loginPage.git

2.Import the project into Eclipse IDE or any Java EE IDE.

3.Set up SQL database using provided schema.

4.Add the SQL JDBC connector JAR file to your project’s lib/ folder.

5.Run the project on Apache Tomcat Server.

📷 Screenshots
📌 Registration Page

![image](https://github.com/user-attachments/assets/0fe33b73-cf41-49d3-a226-b61f71aeb483)


📌 Login Page

![image](https://github.com/user-attachments/assets/0a9918a5-34c2-4df6-80c1-eb4340a0f0c9)


📌 Welcome Page

![image](https://github.com/user-attachments/assets/da7551be-a35d-4aee-83cb-69b4992d43b7)


📌 ViewProfile Page
![image](https://github.com/user-attachments/assets/793b843f-53a9-464f-9670-3f2801cd85a0)


📌 LogOut Page
![image](https://github.com/user-attachments/assets/ad66268d-59a1-4c45-b01b-316dde99ddef)


📖 License
This project is open-source and available under the MIT License.

📞 Contact
Name: Harshad Sonule

GitHub: @HarshadSonule0703

Email: harshadsonule0703@gmail.com
