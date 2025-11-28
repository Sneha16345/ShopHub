🛍️ ShopHub

ShopHub is a modern fullstack e-commerce web application that provides users with a seamless and intuitive shopping experience. Built with Angular and Spring Boot, and powered by PostgreSQL, it delivers a modern, responsive UI combined with a secure and scalable backend.

Customers can effortlessly browse products, manage carts, and place orders. Meanwhile, admins have full control over store operations — performing complete CRUD (Create, Read, Update, Delete) operations on products, managing and updating order statuses, and monitoring weekly sales and earnings through an interactive dashboard. With smooth performance, elegant design, and real-time management tools, ShopHub is a complete fullstack end-to-end solution for online shopping and administration.

✨ Features
👩‍💻 User Features

🧾 Simple and secure login and signup system

🛒 Add, view, update, and remove products from the shopping cart

📦 Browse and search products with filters and categories

💳 Secure checkout process for placing orders

📜 View order history and detailed order statuses

⚡ Fully responsive design optimized for all devices

🧑‍💼 Admin Features

📦 Perform full CRUD operations — add, edit, delete, and view products

📋 Manage and update user orders and their delivery status

📊 View weekly sales, earnings, and performance charts

📈 Dashboard overview with total users, products, and revenue stats

🧰 Manage inventory levels and product availability

🧾 Clean, easy-to-use sidebar navigation for quick access

🛠️ Tech Stack

⚛️ Frontend: Angular (Standalone Components)

🎨 Styling: Bootstrap 5, CSS

🌱 Backend: Spring Boot (REST API Integration)

🗄️ Database: PostgreSQL

📊 Charts & Graphs: ng2-charts / Chart.js

⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/Sneha16345/shophub.git
cd shophub

2️⃣ Install frontend dependencies
cd frontend
npm install

3️⃣ Configure the backend

🟢 Ensure PostgreSQL is installed and running

🗄️ Create a database, e.g., shophub_db

✏️ Update your database credentials in src/main/resources/application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/shophub_db
spring.datasource.username=your_username
spring.datasource.password=your_password

4️⃣ Run the backend
cd backend
./mvnw spring-boot:run

5️⃣ Run the frontend
cd frontend
ng serve

6️⃣ Open in browser

🌐 http://localhost:4200

