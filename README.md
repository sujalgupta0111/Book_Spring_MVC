# 📚 Book Admin management bY MVC

## 📌 Overview
The **Book Admin Module** is a web-based application built on **Spring MVC** and **Spring Boot** that allows administrators to **perform various CRUD operations** on books. The system uses **Thymeleaf** for dynamic rendering, **Hibernate** for ORM, and **MySQL** as the database. The UI is designed using **HTML, Bootstrap**, ensuring a responsive and modern look.

## 🚀 Features
- 📝 **Create, Read, Update, and Delete (CRUD) Books**
- 🔍 **Search & Filter Books**
- 📥 **Download Book Data**
- 🔗 **Seamless MySQL Database Integration**
- 🎨 **User-friendly UI with Bootstrap & Thymeleaf**
- ⚡ **Spring Boot-powered Backend**

## 🏗️ Tech Stack
- **Backend:** 🟢 Spring Boot, Spring MVC
- **Frontend:** 🌐 Thymeleaf, HTML, CSS, Bootstrap
- **Database:** 🛢️ MySQL
- **ORM:** 🔄 Hibernate

## 🛠️ Installation & Setup
### Prerequisites
Make sure you have the following installed:
- ✅ Java (JDK 11+)
- ✅ MySQL
- ✅ Maven
- ✅ IDE (IntelliJ IDEA / Eclipse)

### Steps to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/book-admin-module.git
   cd book-admin-module
   ```
2. **Configure the Database:**
   - Create a MySQL database named `book_admin`
   - Update `application.properties` with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/book_admin
     spring.datasource.username=root
     spring.datasource.password=yourpassword
     spring.jpa.hibernate.ddl-auto=update
     ```
3. **Build and Run the Application:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
4. **Access the App in Browser:**
   ```
   http://localhost:8080
   ```

## 📂 Project Structure
```
📦 book-admin-module
 ┣ 📂 src
 ┃ ┣ 📂 main
 ┃ ┃ ┣ 📂 java
 ┃ ┃ ┃ ┣ 📂 com.bookadmin
 ┃ ┃ ┃ ┃ ┣ 📜 BookController.java
 ┃ ┃ ┃ ┃ ┣ 📜 BookService.java
 ┃ ┃ ┃ ┃ ┣ 📜 BookRepository.java
 ┃ ┃ ┃ ┃ ┗ 📜 Book.java
 ┃ ┃ ┣ 📂 resources
 ┃ ┃ ┃ ┣ 📂 templates (Thymeleaf HTML files)
 ┃ ┃ ┃ ┣ 📂 static (CSS, JS, Images)
 ┃ ┃ ┃ ┣ 📜 application.properties
 ┣ 📜 pom.xml
 ┣ 📜 README.md
```


=

## 🤝 Contributing
Feel free to contribute to the project. Create a pull request with your changes!

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 *Happy Coding!* 🚀

