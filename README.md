## E-commerce Website

This is an e-commerce website built with React, Redux Toolkit, Hooks, Stripe, and Firebase.

### Features

* **Authentication:** User registration and login with Firebase Authentication.
* **Product Listing:** Displays a list of products with details and images.
* **Shopping Cart:** Users can add products to their cart and view the total cost.
* **Checkout:** Integrated with Stripe for secure online payments.
* **Order History:** Users can view their previous orders.
* **Admin Dashboard:** Allows administrators to manage products, orders, and users.

### Technologies Used

* **React:** A JavaScript library for building user interfaces.
* **Redux Toolkit:** A library for managing application state in React.
* **Firebase:** A Backend-as-a-Service (BaaS) platform providing real-time database, authentication, and storage services.
* **Stripe:** A payment processing platform for accepting online payments.
* **React Router:** A library for handling routing in React applications.
* **Material UI:** A popular React component library.

### Getting Started

1. Clone this repository: `git clone https://github.com/simpletut/React-Redux-Firebase-eCommerce-Website.git`
2. Install dependencies: `npm install`
3. Set up a Firebase project and configure it in the `.env` file.
4. Set up a Stripe account and configure it in the `.env` file.
5. Start the development server: `npm start`

### Project Structure

* `src/components`: Contains reusable React components for the UI.
* `src/pages`: Contains the main pages of the application (e.g., home, product, cart, checkout).
* `src/features`: Contains Redux slices for managing different parts of the application state (e.g., products, cart, user).
* `src/firebase`: Contains the Firebase configuration and helper functions.
* `src/stripe`: Contains the Stripe configuration and helper functions.

### Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.
