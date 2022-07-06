# MERN Ecommerce

## Description

An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

1. Buyers browse the store categories, products and brands
2. Sellers or Merchants manage their own brand component
3. Admins manage and control the entire store components

- features:
  - Node provides the backend environment for this application
  - Express middleware is used to handle requests, routes
  - Mongoose schemas to model the application data
  - React for displaying UI components
  - Redux to manage application's state

---

## Database Seed

```diff
- npm run data:destroy
+ npm run data:import
```

---

## ▶️ Demo

This application is deployed on Heroku. Please check it out: [here](https://mern-mlhy.herokuapp.com/)

---

## Install

Some basic Git commands are:

```
$ git clone git@github.com:yosra-hashem/Ecommerce-MERN.git
$ cd project
$ npm install
$ cd frontend
$ npm install
```

---

## Setup

```
 Create .env file that include:

 - MONGO_URI & JWT_SECRET & JWT_EXPIRY
   PORT & BASE_SERVER_URL
 - MAILGUN_API_KEY & MAILGUN_DOMAIN
   EMAIL_FROM => Mailchimp configuration
```

---

## Heroku Deployment

```
> Create a Procfile in the root directory of your application with the following command **web: npm run start:production**
```

---

## How To Use ⬇️

### Start development

```diff
+ $ npm run dev
```

### Simple build for production

```diff
+ $ npm run build
```

### Run build for production

```diff
+ $ npm start
```

---

## Languages & tools

- [Node](https://nodejs.org/en/)

- [Express](https://expressjs.com/)

- [Mongoose](https://mongoosejs.com/)

- [React](https://reactjs.org/)

- [Chakra-ui](chakra-ui)

---
