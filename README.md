# Redux Store-shop-shop

## Overview

Your challenge is uses [Redux](https://redux.js.org/).to build an e-commerce application that allows users to shop items, add products to the shopping cart, manage the shopping cart by increasing and decreasing quantities, check out their purchases and see their order history. 

## Prequisites

* Node.js
* Express.js
* GraphQL 
* Apollo Server 
* MongoDB 
* React 
* Redux
* Stripe

## Install

* GitHub repository: https://github.com/SusanSu123/Redux-shop.git

## Deployment

* Heroku: https://redux-shop-shop-app.herokuapp.com/


## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Mock-Up

This section reviews the web application's general appearance and functionality.

The following animation shows how a user can register using the Signup page and then navigate to the Products page:

![A user registers on the Signup page and then navigates to the Products page, which displays images and descriptions of products.](./22-state-homework-demo-01.gif) 

The following animation shows how the user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:

![The user selects a category, chooses a product, views details about it on the product page, and adds it to and removes it from their shopping cart.](/22-state-homework-demo-03.gif)

Finally, the user can check out by going to their shopping cart, as shown in the following animation:

![The user checks out by going to their shopping cart.](./22-state-homework-demo-03.gif)