

# E-Commerce Platform

This project is a full-stack e-commerce platform built using **Node.js**, **Express.js**, **MongoDB**, and **EJS**. It allows users to browse, add, edit, and manage products. The platform includes essential features such as user authentication, product management, reviews, shopping cart, and wishlist functionalities.

## Features

* **User Authentication**: Secure login/signup system powered by Passport.js for user authentication.
* **Product Management**: CRUD (Create, Read, Update, Delete) operations for managing products.
* **Reviews**: Users can add reviews to products they’ve purchased or viewed.
* **Shopping Cart & Wishlist**: Users can manage items for purchase by adding them to the cart or wishlist.
* **Flash Notifications**: Instant feedback for user actions like adding products to the cart or creating an account.

## Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Templating Engine**: EJS
* **Authentication**: Passport.js

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:


   git clone https://github.com/RiddhiBansal04/E-Commerce-Platform.git
   

3. **Navigate to the Project Directory**:

  
   cd E-Commerce-Platform
 

4. **Install Dependencies**:

  
   npm install


5. **Create a .env File**:
   In the root directory, create a `.env` file and add the following configuration:

  
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/E-Com-DB
   SESSION_SECRET=your-secret-key

   Replace your-random-secure-secret-key with your own long, secure, private string. Do not share this key or commit it to version control.
  

6. **Start the Application**:

   
   npm start
   

7. **Open in Browser**:
   Visit [http://localhost:5000](http://localhost:5000) to view the application.

## Usage

* **Browse Products**: Navigate to `/products` to see the list of available products.
* **Add a New Product**: If logged in as a seller, go to `/products/new` to add a new product.
* **View Product Details**: Click on a product in the list to view its details and reviews.
* **Manage Cart & Wishlist**: Add products to your cart or wishlist for later purchase.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a pull request.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.


