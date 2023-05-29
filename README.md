# AmazonSetuFrontend
https://chic-maamoul-28df3a.netlify.app/
The link to backend of this app:
https://github.com/TezzMore/AmazonSetuBackend


AmazonSetu:
This is a clone of the popular e-commerce shopping app Amazon. It has been developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack and incorporates essential features such as adding items to the cart, payment processing with credit card details, and doorstep delivery. The Stripe API has been utilized for handling payment transactions securely.

Table of Contents:
Features,
Technologies Used,
Installation,
Configuration,
Usage,
Contributing,
License.

Features
User authentication and authorization
Product catalog with search functionality
Product details page
Shopping cart management
Secure payment processing with credit card details via Stripe API
Order history tracking
Delivery address management


Technologies Used
The following technologies and frameworks have been used in the development of this project:

MongoDB: A NoSQL database used for storing product, user, and order data.
Express.js: A web application framework for creating server-side APIs.
React.js: A JavaScript library for building user interfaces.
Node.js: A JavaScript runtime environment for server-side development.
Stripe API: A secure payment processing API for handling credit card transactions.

Installation
To install and run the project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/TezzMore/AmazonSetuFrontend.git
Navigate to the project directory:

bash
Copy code
cd AmazonSetuFrontend
Install the dependencies for both the server and the client:

bash
Copy code
cd server && npm install
cd ../client && npm install


Configuration
Before running the project, you need to configure the following:

MongoDB: Set up a MongoDB database and configure the connection string in the server/.env file.

Stripe API: Sign up for a Stripe account and obtain the necessary API keys. Set these keys in the server/.env file.

Usage
To start the project, follow these steps:
In the server directory, start the server:

bash
Copy code
npm start
In the client directory, start the client:

bash
Copy code
npm start
Access the application by opening your browser and navigating to http://localhost:3000.

Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
Fork the repository.
Create a new branch for your feature or bug fix:

bash
Copy code
git checkout -b feature/your-feature-name
Make your changes and commit them:

bash
Copy code
git commit -m "Add your commit message here"
Push your changes to your forked repository:

bash
Copy code
git push origin feature/your-feature-name
Open a pull request to the main repository's main branch.
