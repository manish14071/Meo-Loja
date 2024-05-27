eCommerce_MERN_app 🛒
![thumb](https://github.com/manish14071/Meo-Loja/assets/89667128/5128818d-fcdc-4ef8-b3e3-34e1cfcab3f8)
Logo

Version 1 :
The data is stored using MongoDB
Stripe integration for payment.
For payment and order information used firestore.
Yet, Features and improvements required in admin panel. version 1 is hosted HERE!
An E commerce platform made using React JS, Redux, MaterialUI, Router, ExpressJS, MongoDB, Firestore, Stripe API (temporarily creating dummy payment gateway).

The application is composed of the following Features:
Front-End
A landing page with animated minimalistic design, with the major categories of items.
A quick peek page where 5 products of each categories are on display.
A page with Sign-in and Sign-out components.
All form related fields are made using reusable components.
Has a cart feature which opens up and displays the items selected in a summary, also has a checkout button.
The cart component also allows to edit the contents of the items selected.
Checkout features are integrated with the appplication.
Backend
API Endpoints: Various API endpoints manage CRUD operations for products, categories, users, and more.

Authentication: Secure Sign-in and Sign-out components ensure user access control through authentication tokens.

Reusable Components: Form-related fields are designed as reusable components for maintainability and extensibility.

Cart Management: Users can add and remove items, and update quantities in their shopping cart.

Payment
Secure Payments: Stripe API integration enhances the application's payment processing capabilities, providing a secure and reliable payment gateway for online transactions.

Order Storage: Completed orders are meticulously stored in Firestore, guaranteeing the preservation of order details for future reference and fulfillment.

Seamless Payment Flow: The Stripe integration ensures a seamless payment flow within the application, allowing users to complete transactions swiftly and securely, enhancing the overall shopping experience.

Admin panel Here
SCREENSHOTS:
Landing Page:


Product Preview:

   
Sign-in && Sign-Up Page:

 


Cart Section:



Payment:



Developed With
Visual Studio Code - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
React - A javascript library for building user interfaces
Create react app - A quick method to start developing a react application.
Babel - A transpiler for javascript
Webpack - A module bundler
MaterialUI - A prebuilt comp. provider
ExpressJS - A web application framework for Node.js.
NodeJS - A JavaScript runtime for server-side applications.
MongoDB - A NoSQL database system.
Firestore - A cloud-based NoSQL database service from Firebase.
Stripe - A payment processing platform for online businesses.
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
The following software is required to be installed on your system:

Node 20.x
Npm 8.x
Type the following commands in the terminal to verify your node and npm versions

node -v
npm -v
How to Run
Clone the Repository: Start by cloning this repository to your local machine.

Backend Setup:

Navigate to the backend directory and run npm install to install the required backend dependencies.
Configure the database and environment variables as specified in the backend documentation.
Run npm start to start the server.
Frontend Setup:

Navigate to the frontend directory and run npm install to install the required frontend dependencies.
Configure the frontend environment variables as necessary.
Run npm start to launch the frontend.
Access the Application:

Visit the application in your web browser at http://localhost:6000 (by default for the frontend).
Ensure the backend is running on a different port as specified in your configuration.
Feel free to explore and build upon this project to create a fully functional e-commerce application. For any questions or assistance, please don't hesitate to reach out to us. Happy coding and happy shopping!
