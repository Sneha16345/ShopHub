🛍️ ShopHub

ShopHub is a modern full-stack e-commerce web application providing users with a seamless and intuitive shopping experience. Built with Angular for the frontend, Spring Boot for the backend, and powered by PostgreSQL, ShopHub delivers a responsive, secure, and scalable platform for both customers and admins.

Customers can browse products, manage carts, and place orders effortlessly, while admins enjoy full control over store operations, including product management, order tracking, and analytics.

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
  
  📋 Manage and update user orders and delivery statuses
  
  📊 View weekly sales, earnings, and performance charts
  
  📈 Dashboard overview with total users, products, and revenue stats
  
  🧰 Manage inventory levels and product availability
  
  🧾 Clean, easy-to-use sidebar navigation for quick access

🛠️ Tech Stack

⚛️ Frontend: Angular (Standalone Components)

🎨 Styling: Bootstrap 5, CSS

🌱 Backend: Spring Boot (REST API)

🗄️ Database: PostgreSQL

📊 Charts & Graphs: ng2-charts / Chart.js

⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/Sneha16345/shophub.git
cd shophub

2️⃣ Install frontend dependencies
cd ShopHub-frontend
npm install

3️⃣ Configure the backend

Ensure PostgreSQL is installed and running

Create a database, e.g., shophub_db

Update your database credentials in ShopHub-backend/src/main/resources/application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/shophub_db
spring.datasource.username=your_username
spring.datasource.password=your_password

4️⃣ Run the backend in IntelliJ

Open IntelliJ IDEA → File → Open → ShopHub-backend

Wait for Maven to import all dependencies

Locate the main class (ShopHubBackendApplication.java)

Right-click → Run 'ShopHubBackendApplication'

Backend will start on http://localhost:8080

5️⃣ Run the frontend
cd ShopHub-frontend
ng serve

6️⃣ Open in browser

🌐 http://localhost:4200