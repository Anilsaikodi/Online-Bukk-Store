# Book Store MERN
A website made by MERN STACK. It allows customers to buy books through Paypal account.
# Installation
run mongodb before you start.

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
Express js
React js
Node js

BACKEND:
Mongodb



### Project Overview
PROJECT OVERVIEW:
Bukk Store Website is the one kind of web application which integrates all the modules and functionalities of Ecommerce website that can be handled by admin or employee and access by customers with valid email and password. It is used to manage the activities which include the management of books, customers, genres, employees and orders. It provides one-point access to manage these wide range of activities both effectively and efficiently. 

### Admin Module
ADMIN MODULE:
 Admin can login using valid credentials and perform various task such as Adding a Another Employee, Books and Genres. Admin can see the orders what customer placed and he can give an update about delivery when it get deliver. 

### Env Variables

Create a .env file in then root and add the following


NODE_ENV = development
PORT = 3001
MONGO_URI = your mongodb uri
JWT_SECRET = your secret key
PAYPAL_CLIENT_ID = your paypal client id

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
