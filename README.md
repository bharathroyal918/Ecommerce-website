🛒 E-Commerce Website
This is a simple e-commerce website built with PHP, MySQL, HTML, CSS, and JavaScript. It provides an online shopping platform where users can browse products, add them to the cart, and make purchases. An admin panel allows product management.

🚀 Features
User Side:
🛍️ View available products with images and descriptions.
🛒 Add products to the shopping cart.
🔐 User authentication (Login & Registration).
📦 Checkout system (to be implemented).


Admin Panel:
➕ Add new products.
📝 Edit or update product details.
❌ Delete products from the store.

🛠️ Technologies Used
Backend: PHP & MySQL (PDO for database interaction)
Frontend: HTML, CSS, JavaScript, Bootstrap
Authentication: PHP sessions
Database: MySQL


📂 Project Structure
bash
Copy
Edit
/ecommerce
│── /images        # Product images
│── /includes      # Database connection
│── /pages         # User authentication & cart
│── /admin         # Admin panel for managing products
│── index.php      # Homepage
│── styles.css     # Styling
│── db.php         # Database connection file


📌 Setup Instructions
Clone this repository:
git clone https://github.com/your-username/ecommerce.git
Import the ecommerce.sql database (provided).
Update includes/db.php with your database credentials.
Start a local server (XAMPP, WAMP, or MAMP).
Open index.php in a browser.
