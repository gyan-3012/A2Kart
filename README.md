
# A2Kart

A2Kart is a fully-fledged MERN stack e-commerce application that enables users to browse, search, and purchase products online, while providing admins with a secure and intuitive dashboard to manage the store's inventory, orders, and customers.

## Features

### User Features

- Create an account and log in to the application
- Browse and filter products by their name
- Add items to their shopping cart and complete the checkout process
- Track their orders and leave reviews or ratings for products

### Admin Features

- Secure and intuitive dashboard to manage the store's inventory, orders, and customers
- Add and edit products
- Manage orders and shipments
- Track sales and customer data


## Tech Stack

- MongoDB: A NoSQL database used to store the application's data
- Express.js: A web application framework for Node.js used to build the application's backend
- React.js: A JavaScript library used to build the application's frontend
- Node.js: A JavaScript runtime used to execute the application's server-side code


## Live Application

https://a2kart.onrender.com/
## Dummy Accounts

Some dummy accounts to check the functionality of live Application.

### Admins

- email: admin@example.com, password: admin_30

### Users

- email: gyan@example.com, password: gyan_30
- email: shiv@example.com, password: shiv_30
- email: vishal@example.com, password: vishal_30
- email: deepak@example.com, password: deepak_30
- email: shobhit@example.com, password: shobhit_30
## Run Locally

Clone the project

```bash
  git clone https://github.com/gyan-3012/A2Kart.git
```

Go to the project directory
    
```bash
  cd A2Kart
```

Install dependencies

```bash
  npm install && npm install --prefix frontend
```

Start the server
 
```bash
  npm run dev
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in root directory

`NODE_ENV = 'development'`

`PORT = 5000`

`MONGO_URI`

`JWT_SECRET`

`PAYPAL_CLIENT_ID`


## Contributions

We welcome contributions to A2Kart. If you have an idea for a new feature or have found a bug, please open an issue in the repository. If you would like to contribute code, please fork the repository and create a new branch with your changes. When you are ready to submit your changes, please create a pull request to the master branch.

