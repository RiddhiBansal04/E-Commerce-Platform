# E-Commerce-Platform
E-Commerce Platform
This project is a full-stack e-commerce platform built with Node.js, Express.js, MongoDB, and EJS. It allows users to browse, add, edit, and manage products. The platform includes features such as user authentication, product reviews, and cart management.

Features
User Authentication: Secure login/signup using Passport.js.
Product Management: CRUD operations for products (create, read, update, delete).
Reviews: Users can add reviews for products.
Shopping Cart & Wishlist: Manage items for purchase.
Flash Notifications: Feedback messages for user actions.


Tech Stack
Backend: Node.js, Express.js
Database: MongoDB
Templating: EJS

Installation
Clone the Repository:
git clone https://github.com/your-username/e-commerce-project.git

Navigate to the Project Directory:
cd e-commerce-project

Install Dependencies:
npm install

Create a .env File:
In the root directory, create a file named .env and add the following configuration:
PORT=5000
MONGODB_URI=mongodb://localhost:27017/E-Com-DB
SESSION_SECRET=your-secret-key

Start the Application:
npm start

Open in Browser:
Visit http://localhost:5000 to view the application.

Usage
Browse Products:
Navigate to /products to see the list of available products.

Add a New Product:
If logged in as a seller, go to /products/new to add a new product.

Product Details:
Click on a product in the list to view its details and reviews.

Manage Cart & Wishlist:
Add products to your cart or wishlist for later purchase.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.