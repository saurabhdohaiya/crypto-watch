# CryptoClock

**CryptoClock** is a real-time cryptocurrency price tracking web application built using ReactJS, Material UI, Firebase, ChartJS, and React Context API. The application provides live updates on cryptocurrency prices, offering insights into price changes over various timeframes ranging from 24 hours to a year. The project emphasizes data visualization and secure user authentication to enhance user engagement and experience.

## Features

- **Real-time Cryptocurrency Tracking:**  
  Track cryptocurrency prices in real time, with updates spanning from 24-hour to 1-year timeframes.

- **Data Visualization with ChartJS:**  
  Interactive charts built with ChartJS to display trends and price changes over time, providing a clear and engaging visual representation of data.

- **Secure Authentication System:**  
  Users can securely sign up and log in using Firebase authentication, with added security measures to protect against unauthorized access.

- **User Dashboard:**  
  Personalized user dashboard displaying the tracked cryptocurrencies and their current values. The dashboard updates automatically based on user preferences and latest market data.

- **Responsive Design:**  
  The app is fully responsive, designed with Material UI for a seamless experience across devices of all screen sizes.

## Tech Stack

- **Frontend:**
  - ReactJS
  - Material UI
  - CSS
  - ChartJS (for data visualization)
  - React Context API (for state management)

- **Backend:**
  - Firebase (authentication and database)

## Project Setup

To run this project locally, follow the steps below:

### Prerequisites

- Node.js
- Firebase account (for authentication and database setup)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/cryptoclock.git
   cd cryptoclock
  `
## Screenshots

Here are a few screenshots showcasing the user interface and features of **CryptoClock**:

### Home Page
![Home Page](./screenshots/home-page.png)  
_Real-time cryptocurrency tracking with data visualization._

### Login Page
![Login Page](./screenshots/login-page.png)  
_Secure authentication system using Firebase._

### Dashboard
![Dashboard](./screenshots/dashboard.png)  
_Interactive user dashboard showing cryptocurrency price trends over different timeframes._

> Note: You can add your actual image files to the `screenshots` folder in your project and replace the placeholder paths above with the correct image file paths.

## Login

The application uses **Firebase** for user authentication, providing a secure login and signup system. Here’s how the login process works:

1. **User Signup:**  
   New users can sign up using their email and password, which is securely stored in Firebase Authentication.

2. **User Login:**  
   Returning users can log in using their credentials, allowing them to access their personalized dashboard and cryptocurrency data.

3. **Secure Authentication:**  
   Firebase Authentication ensures secure login and signup, with protection against unauthorized access.

### How to Use the Login System

1. Navigate to the **Login Page**.
2. If you don’t have an account, click on **Sign Up** and create an account with your email and password.
3. Once signed up, you can log in with your credentials to access your dashboard.

The authentication system ensures that users' data remains private and secure, providing a smooth and safe experience.
