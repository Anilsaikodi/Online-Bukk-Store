# Book Store MERN
A website made by MERN STACK. It allows customers to buy books through Paypal account.
# Installation
run mongodb before you start.

## Project Overview
PROJECT OVERVIEW:
Online Book store is an online web application where the customer can purchase books online. Through a web browser the customers can search for a book by its title, later can add to the shopping cart and finally purchase using credit card transaction. The user can login using his account details or new customers can set up an account very quickly. They should give the details of their name, contact number and shipping address. The user can also give feedback to a book by giving ratings on a score of five. The books are divided into many categories based on genres like action, adventure, romance, comics etc.., 

## Admin Module
ADMIN MODULE:
 Admin can login using valid credentials and perform various task such as Adding a Another Employee, Books and Genres. Admin can see the orders what customer placed and he can give an update about delivery when it get deliver. 

## Features

- Full featured shopping cart
- Product pagination
- Product search feature
- User profile with orders
- Change Password
- Admin product and genres management
- Admin customer management
- Admin Employee management
- Admin Order details page
- Admin Statistics for income
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (books & users & genres & Customers)


FRONTEND:
Express js,
React js,
Node js

BACKEND:
Mongodb



### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 3001
MONGO_URI = your mongodb uri
JWT_SECRET = your secret key
PAYPAL_CLIENT_ID = your paypal client id
```

Start Server
```
npm install
npm run dev
```

Start Client Side
```
cd client
npm install
npm start 
```
