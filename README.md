# MERN Ecommerce
>React Node Ecommerce application with Paypal and Credit Card payments with Admin Order Management System.

## Table of contents
* [Description](#description)
* [Live Demo](#live-demo)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Contact](#contact)

## Description
An ecommerce  built with MERN stack, and utilizes third party API's. This ecommerce store enable two main different flows or implementations:

1. Buyers browse the store categories and products
2. Admins manage and control the entire store components 


## Live Demo
Here is a working live demo :  

Use the below login so you can access admin areas:
- Email: admin@gmail.com
- Password: 12345

Use the below card to pay with Paypal or Credit Card:
- 4111 1111 1111 1111 - 01/25 - 111


## Screenshots

### Landing Page
![landing](https://user-images.githubusercontent.com/31744209/100269984-702c7c80-2f68-11eb-9de9-7330abce40e1.png)


### Shopping Page
![shop](https://user-images.githubusercontent.com/31744209/100269951-63a82400-2f68-11eb-8afb-62e7cc04f685.png)


### Cart Page
![shopping-cart](https://user-images.githubusercontent.com/31744209/100269957-660a7e00-2f68-11eb-8c10-48273dc3f336.png)


### Signup Page
![signup](https://user-images.githubusercontent.com/31744209/100269961-686cd800-2f68-11eb-831f-ff3116bb1d51.png)


### Signin Page
![signin](https://user-images.githubusercontent.com/31744209/100269959-673bab00-2f68-11eb-95d4-6736aac86569.png)


### User-dashboard Page
![user-dashboard](https://user-images.githubusercontent.com/31744209/100269966-6acf3200-2f68-11eb-80a2-1a77c41ecaa5.png)


### Admin-dashboard Page
![admin-dashboard](https://user-images.githubusercontent.com/31744209/100269980-6efb4f80-2f68-11eb-92db-977e991ca788.png)


## Technologies
* Technologies used:
  * `React` 16.8 - for displaying UI components
  * `Bootstrap` 4.3 -  CSS Framework for developing responsive and mobile-first websites
  * `Node` 12.1 - provides the backend environment for this application
  * `Moongoose` 5.5 - Mongoose schemas to model the application data
  * `Express` 4.16 - middleware is used to handle requests, routes


## Setup
To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer.

###  Clone repo
Run the following scripts in the terminal to clone the repo
```
$ git clone git@github.com:jamesmogambi/MERN-Ecommerce.git
$ cd MERN-Ecommerce
```

----------------------------------

### Start Backend
 #### 1. Setup MongoDB
 - Download and Install it from [mongodb.com](https://www.mongodb.com/try/download/community)
 
 #### 2. Get Braintree Credentials
 - Get braintree test credentials from [Braintree](https://www.braintreepayments.com/sandbox)
 
 #### 3. Go to backend folder
  - Open the terminal and run the following script:
  
  ```
  # Go to backend directory
  $ cd backend
  ```
  
 #### 4. Create .env file
- Create .env file in project folder
- Enter these lines to that:

```
DATABASE=mongodb://localhost/ecommerce
PORT=8000
JWT_SECRET=somethingsecret
BRAINTREE_MERCHANT_ID=braintree merchant id
BRAINTREE_PUBLIC_KEY=braintree public key
BRAINTREE_PRIVATE_kEY=braintree private key

```
 #### 5. Run Backend

```bash
# Install dependencies
$ npm install

# Run the app
$ npm start
```


### Start Frontend
 #### 1. Go to frontend folder
  - Open the terminal and run the following script:
  
  ```bash
    # Go to frontend folder
    $ cd backend
    ```
 #### 2. Create .env file
Make sure to setup the url for the backend server.
Hence:
- Create .env file in project folder
- Enter these line to that:

```
REACT_APP_API_URL=url for the backend server

```

#### 3. Run frontend

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

In the project directory, you can run:

##### `npm install`

Installs all the dependencies.<br>
All dependecies are listed in package.json file in the root directory.


##### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

##### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

##### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

##### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

#### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

#### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

#### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

#### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

#### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify



## Features
List of features:
* Search products
* Search products based on particular category
* New arrivals
* Best sellers
* Product image
* Product information
* Product in stock/out of stock
* View product
* Related product
* Add to cart
* Remove product
* Adjust quantity
* Signin to checkout
* User dashboard
* Admin dashboard
* Private routes
* Admin routes
* Shopping cart
* Checkout with credit card and paypal
* Checkout with delivery address
* Success message
* Update profile
* Advance search of products
* Advance search based on category and price range
* Load more products
* Admin dashboard
* Create category
* Create product
* View orders
* Manage products update/delete
* Role based access


To-do list:
* Add local payment gateways
* Add password reset 

## Status
Project is: _in progress_,some adjustments are in development.

## Contact
Created by [@jamesmogambi](https://github.com/jamesmogambi/) - feel free to contact me!
