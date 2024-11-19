# Full-Stack Banking Application

## Description/Motivation
The Full-Stack Banking Application is designed to simplify personal finance management by providing a secure, user-friendly platform for users to perform essential banking operations. Built using the MERN stack (MongoDB, Express, React, Node.js), this project demonstrates the integration of front-end and back-end technologies to create a full-stack application.

This application helps users manage their accounts effectively by offering features such as secure login, deposits, withdrawals, and persistent account management. It is ideal for showcasing practical development skills and solving real-world problems by addressing the need for a seamless banking experience.

## Features
- **User Authentication:** Secure account creation, login, and OAuth2 support.
- **Account Management:** Persistent user accounts with real-time balance updates.
- **Transactions:** Deposit and withdraw money with instant feedback.
- **User Roles:** (Optional) Role-based access control for customers and employees.
- **Account Types:** Support for checking and savings accounts.
- **Enhanced Features:** Random account number generation, user profile updates, and optional check deposits via photo uploads.
- **Deployment:** The application is deployed to a cloud service for accessibility.

## Installation Guidelines
1. Clone the repository: `git clone https://github.com/LucaBrizuela/Tiered-Bad-Bank.git`
2. Navigate to the project directory: `cd Tiered-Bad-Bank`
3. Install dependencies:`npm install`
4. Set up the environment variables:
- Create a .env file in the root directory.
- Add the following variables:
   ```env
   MONGO_URI=your-mongodb-connection-string
   JWT_SECRET=your-secret-key

5. Start the development server: `npm start`

6. Access the application in your browser at `http://localhost:3000.`

## Screenshots

### User Dashboard

![User Dashboard](screenshot1.png)

---

## Technology Used

- **Frontend:** React, CSS  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Authentication:** JSON Web Tokens (JWT), OAuth2  
- **Deployment:** Cloud service provider (e.g., Heroku, AWS, or Vercel)  

---

## Roadmap

### Future Features

- **Enhanced Authorization:** Role-based controls for customers and employees.  
- **Check Deposit:** Capture check images for digital deposits.  
- **Improved User Interface:** Add themes and customization options.  
- **Advanced Analytics:** Include graphs and reports for financial insights.  

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/LucaBrizuela/Tiered-Bad-Bank/blob/main/LICENSE) file for details.

