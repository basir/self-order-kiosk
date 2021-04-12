# Food Self-Order Kiosk
Welcome to my coding course to build a Self-Order Kiosk like Macdonalds. In this course, you will learn the essential tools and skills to a web application for Self-Order Kiosk using React, Context API, and Material UI in the frontend and Node and MongoDB in the backend.

My name is Basir and I'll be your instructor in this course.

By the end of this course, you will be able to build a professional and fully-functional web application to launch on a self-order kiosk in a restaurant.
In this path, you will learn the modern React concepts and libraries: 
- Material UI to build professional looking web applications
- Themes, Animations, Modals, Boxes, Forms and etc
- React Hooks like useState and useReducer to manage state in single components
- Context API to handle complex states between multiple components
-  Node and Express to build a simple simple and elegant backend
- MongoDB and Mongoose to manage orders in the backend
- Heroku to deploy your web application on cloud servers

This course is for non-coders or juniors who want to be a pro developer and find a job in 22 million job opportunities around the world.

Knowing React basics like component, state and props are the only requirements for this course.

Feel free to take a look at the course preview and enroll if it is along with your ambitions.


## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:basir/self-order-kiosk
$ cd self-order-kiosk
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/self-order-kiosk  
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm run server
```

### 4. Run Frontend

```
# open new terminal
$ npm start
```

### 5. Seed Sample Data

- Open: http://localhost:5000/api/products/seed
- It creates 9 sample products

### 6. Open App

- Open: http://localhost:3000


# Lessons
1. Introduction
2. Create home screen
   1. install vs code and chrome
   2. crate react app
   3. create screens/HomeScreen.js
3. Create choose order type screen
   1. Create Choose Order Screen
   2. Create React Context
   3. Create Set Order Type Action
   4. Redirect user to order screen
4. Create backend api for categories
   1. create server.js
   2. create data.js with sample data
   3. return categories
5. List categories
   1. Create Order Screen
   2. get categoryList from context
   3. list categories in use effect
   4. show categories in left side
6. Create backend api for products
   1. connect to mongodb and use mongoose
   2. create product model
   3. seed products
   4. create api for products
7. List products
   1. get productList from context   
   2. list products in use effect
   3. show products in main section
8. Add & remove food to order
   1. create add to order modal
   2. create addToOrder action
   3. create removeFromOrder action
   4. create my order section
   5. handle cancel order
   6. handle finish order
9. Create review order screen
   1.  Create review screen
   2.  add or remove items
   3.  cancel or proceed to checkout
10. Create select payment screen
    1.  Create select screen
    2.  show payment options
    3.  create payment screen
    4.  redirect to complete screen
11. Complete order
    1. create order model  
    2. build backend api
    3. create complete order screen
12. Publish to heroku
    1.  create Procfile
    2.  serve build folder
    3.  send index.html file
    4.  create heroku account
    5.  install heroku cli
    6.  create cloud mongodb database
    7.  get connection string from cloud mongodb
    8.  put it in heroku
    9.  seed data
    10. test web app on heroku
13. Create Admin Screen
    1.  build list order api
    2.  show order in the screen
    3.  create ready, cancel and deliver button
14. Create Queue Screen
    1.  build list queue order api
    2.  show queue in the screen in 2 columns