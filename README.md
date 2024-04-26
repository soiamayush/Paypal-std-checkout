![PayPal Developer Cover](https://github.com/paypaldev/.github/blob/main/pp-cover.png)

# PayPal React (NodeJS) FullStack Standard Checkout

This sample app shows you how to integrate PayPal into your React app for the [standard checkout](https://developer.paypal.com/docs/checkout/standard/integrate/) workflow.

## Run this project

### Locally

Follow the instructions below.

First, install the frontend and backend dependencies with `npm install`.

### Config Frontend

- Inside of the `client/App.jsx` file, enter your PayPal `client-id` inside the `initialOptions` object.

### Config Backend

- Inside the `.env` file, enter your PayPal client ID for the `PAYPAL_CLIENT_ID` and your PayPal app secret for the `PAYPAL_CLIENT_SECRET` environment variables.

### Run app

In the root folder, run `npm start` in your terminal. This will run the backend and frontend at the same time.

- Navigate in your browser to `http://localhost:3000/`

### Sample Card

Card Type: `Visa`

Card Number: `5458406954745076`

Expiration Date: `01/2025`

CVV: `123`

## PayPal Developer Community

The PayPal Developer community helps you build your career while improving your products and the developer experience. You’ll be able to contribute code and documentation, meet new people, and learn from the open-source community.

- Website: [developer.paypal.com](https://developer.paypal.com)
