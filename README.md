
# Advanced Java Programs  

This repository contains various **Advanced Java programs**, including **JDBC, Servlets, and JSP**.  
All programs have been developed and executed using **Eclipse IDE**.  

## 🛠 Prerequisites  

Before running the programs, ensure you have the following:  

- **Eclipse IDE** (for writing and executing Java programs)  
- **XAMPP Server** (for running the MySQL database using phpMyAdmin)  
- **MySQL Connector JAR** (required for JDBC connection)  
- **Apache Tomcat** (for deploying and running Servlets & JSP applications)  

## ⚡ Setup Instructions  

### 1️⃣ Setting Up MySQL Database  
1. Start **XAMPP** and ensure **Apache** & **MySQL** services are running.  
2. Open **phpMyAdmin** (`http://localhost/phpmyadmin/`) and create a database.  
3. Use SQL scripts or JDBC programs to create and populate tables.  

### 2️⃣ Adding MySQL Connector JAR  
1. Download the **MySQL Connector JAR** from the [official site](https://dev.mysql.com/downloads/connector/j/).  
2. In Eclipse, right-click your project → **Build Path** → **Add External JARs...**  
3. Select the downloaded JAR file and click **Apply and Close**.  

### 3️⃣ Configuring Apache Tomcat  
1. Download and install **Apache Tomcat** from [tomcat.apache.org](https://tomcat.apache.org/).  
2. In Eclipse, go to **Window** → **Preferences** → **Server** → **Runtime Environments**.  
3. Click **Add**, select the Tomcat version, and set the Tomcat installation directory.  

## 🚀 Running the Programs  


### JDBC Programs  
1. Ensure MySQL is running via **XAMPP**.  
2. Compile and run JDBC Java files in **Eclipse**.  

### Servlet & JSP Programs  
1. Deploy the project to **Apache Tomcat** inside Eclipse.  
2. Run the application and access it via `http://localhost:8080/YourProjectName/`.  

## 📝 Notes  
- Always configure the **database URL, username, and password** correctly in JDBC programs.  
- Ensure the **web.xml** file is properly configured for Servlet deployment.  




