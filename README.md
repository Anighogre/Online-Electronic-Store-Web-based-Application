# 🛒 Electronic Store – Java Web Application (JSP + Servlet + JDBC)

This is a fully functional **Electronic Store Management System** built using  
**Java, JSP, Servlets, JDBC, MySQL, HTML, CSS, Bootstrap**, and deployed locally on Apache Tomcat.

The project allows **Admins** to manage products and **Customers** to browse & buy products.

---

## 🚀 Features

### 👤 Admin Panel
- Add new products  
- View all products  
- Update product details  
- Delete products  
- Secure admin login  

### 🛍 Customer Panel
- Customer registration & login  
- View available products  
- Buy products with quantity check  
- Order confirmation page  

---

## 🏗 Tech Stack

| Layer | Technology |
|------|------------|
| Language | Java (JDK 8+) |
| Backend | Servlets + JSP |
| Frontend | HTML, CSS, Bootstrap |
| Database | MySQL / Oracle |
| Server | Apache Tomcat |
| Build Tool | WAR Packaging |
| IDE Used | Eclipse / IntelliJ |

---

## 📁 Project Structure

```
ElectronicStore/
│── src/
│   ├── com.ani.pack1 (Servlets + Java Beans)
│── WebContent/
│   ├── JSP Pages
│   ├── CSS / Images
│── database.sql
│── README.md
│── pom.xml (if using Maven)
│── electronic-store.war
```

---

## 🛠 Setup Instructions (Local Machine)

### 1️⃣ Clone Repository
```bash
git clone https://github.com/yourusername/electronic-store.git
```

### 2️⃣ Import into Eclipse
- File → Import → Existing Projects into Workspace  
- Select the project folder  

### 3️⃣ Configure Tomcat
- Add Tomcat 9/10 in Eclipse  
- Right-click project → Run on Server  

### 4️⃣ Configure Database
Run the included SQL script:

```sql
CREATE DATABASE electronic_store;
USE electronic_store;
-- Tables for admin, customer, and products
```

Update DB credentials in:

```
src/com/ani/pack1/ConnectionFactory.java
```

---

## 💡 Screenshots

> *(Add screenshots folder and paste images)*  

- Login Page  
- Admin Dashboard  
- Product Management  
- Customer View  
- Order Success Page  

---

## 🌐 Deployment

This project uses **JSP + Servlet**, so it cannot run on GitHub Pages.  
To deploy online, use:

✔ Railway (Docker + Tomcat)  
✔ Render.com  
✔ AWS EC2  
✔ DigitalOcean  
✔ cPanel (if Tomcat supported)

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Anirudh Ghogre**  
Java Developer | Full Stack Java Intern  
