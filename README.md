📚 Online Book Store – Java Web Project
The Online Book Store is a full-stack web application developed using Java (Servlets & JSP), MySQL, and HTML/CSS. This project allows users to search, browse, and purchase books online. Sellers can list books for sale, while admins manage users and inventory. It’s a complete e-commerce simulation tailored to learning and practicing Java EE (Enterprise Edition) and MVC architecture.

📌 Table of Contents
🔧 Project Overview

🛠️ Technologies Used

🎯 Core Features

🔍 Project Structure

📸 Screenshots

⚙️ Setup Instructions

🚀 Future Enhancements

🙋‍♂️ Author

📜 License

🔧 Project Overview
This Book Store application allows:

Users to create accounts, browse and buy books.

Sellers to upload and manage their book listings.

Admins to control users, sellers, and inventory.

It follows a Model-View-Controller (MVC) architecture, where:

Model = JavaBeans + MySQL

View = JSP + HTML/CSS

Controller = Java Servlets

🛠️ Technologies Used
Layer	Technologies
Frontend	HTML5, CSS3
Backend	Java Servlets, JSP
Database	MySQL
Server	Apache Tomcat 9.0+
IDE	Eclipse (Java EE)
Version Control	Git & GitHub

🎯 Core Features
👤 User Side
Register and login

View all available books by category

Search books by title or author

View book details (title, author, price, image, description)

Add to cart and confirm orders

View order history

📦 Seller Side
Seller registration and login

Add new books with all metadata

Edit or delete books

View uploaded book list

🛡️ Admin Side
Admin login panel

Manage users and sellers (activate/deactivate/delete)

View, edit, or remove any book

View all orders placed

🔍 Project Structure
plaintext
Copy
Edit
OnlineBookStore/
│
├── WebContent/
│   ├── css/                  # Custom CSS styles
│   ├── images/               # Book cover and icon images
│   ├── pages/                # JSP pages (UI)
│   ├── favicons/             # Website favicon set
│   └── index.jsp             # Homepage
│
├── src/
│   ├── com.bookstore.dao/    # Database interaction classes
│   ├── com.bookstore.model/  # JavaBeans (POJOs)
│   ├── com.bookstore.servlet/# Controller servlets
│   └── DBConnection.java     # MySQL DB configuration
│
├── database/
│   └── bookstore.sql         # Full DB schema and sample data
│
└── README.md
📸 Screenshots
(Save your screenshots in the /images folder and update the paths below.)

🏠 Home Page
![Home Page](screenshots/student_dashboard.png)

🔐 User Login
![User Login](screenshots/student_dashboard.png)

📚 Browse Books
![Browse Books](screenshots/student_dashboard.png)

🧾 Admin Dashboard
![Admin Dashboard](screenshots/student_dashboard.png)


⚙️ Setup Instructions
✅ Prerequisites
Java JDK 8 or higher

Apache Tomcat 9.0+

Eclipse IDE with EE support

MySQL server

🔧 Steps
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/OnlineBookStore.git
Import into Eclipse

Open Eclipse → File → Import → Dynamic Web Project → Select folder

Configure MySQL

Create a new database bookstore

Import bookstore.sql from /database folder

Update DBConnection

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/bookstore";
String username = "root";
String password = "your_password";
Deploy to Tomcat

Add project to Tomcat server from Eclipse

Run project on http://localhost:8080/OnlineBookStore/

🚀 Future Enhancements
✅ Payment gateway integration (e.g. Razorpay, Paytm)

✅ Add ratings and reviews system

✅ Wishlist & notification module

✅ Mobile responsive UI using Bootstrap

✅ Session timeout management

✅ Email verification on registration

🙋‍♂️ Author
Harshit Singh
Java Developer | Full Stack Enthusiast
📫 GitHub: Harshit20-sys

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.


