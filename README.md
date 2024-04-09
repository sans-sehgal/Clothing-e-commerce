# CRWN Clothing

CRWN Clothing is an e-commerce website project built using React.js. This project is developed as part of the "Complete React Developer" course by Zero To Mastery (ZTM) on Udemy.

## Description

CRWN Clothing is a modern, responsive e-commerce platform where users can browse through a variety of clothing items, add them to their cart, and proceed to checkout. The project utilizes React.js for the frontend development, integrating with Firebase for authentication and data storage.

## Features

- User authentication: Sign up and login functionalities for users.
- Product browsing: Users can browse through different clothing items available for purchase.
- Shopping cart: Users can add items to their cart and view the total before proceeding to checkout.
- Checkout process: Integration with a payment gateway to process transactions securely.
- Responsive design: Ensures a seamless experience across different devices and screen sizes.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/crwn-clothing.git`
2. Navigate to the project directory: `cd crwn-clothing`
3. Install dependencies: `npm install`
4. Set up Firebase:
   - Create a Firebase project at [https://firebase.google.com](https://firebase.google.com)
   - Enable Authentication and Firestore in Firebase console
   - Create a `.env` file in the root directory and add your Firebase configuration:
     ```
     REACT_APP_FIREBASE_API_KEY=your_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     REACT_APP_FIREBASE_APP_ID=your_app_id
     ```
5. Start the development server: `npm start`

## Credits

- This project is based on the "Complete React Developer" course by Zero To Mastery (ZTM) on Udemy.
- Special thanks to Andrei Neagoie for his guidance and teaching throughout the course.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
