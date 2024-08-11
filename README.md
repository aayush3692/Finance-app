# CS50x : Finance

## Overview
This is the Finance problem set from Harvard's CS50x: Introduction to Computer Science course. In this project, you can see a web application that allows users to "buy" and "sell" stocks, effectively simulating a basic stock trading platform. The project focuses on working with HTML, CSS, JavaScript, and Python using the Flask framework.

## What the Website Does

The Finance website is a stock trading simulation platform where users can create an account, manage a portfolio, and simulate buying and selling stocks using real-time stock data. Here are the main features and functionalities of the website:

### User Registration and Authentication
- **Registration**: Users can create a new account by providing a username and password. The registration system ensures that usernames are unique and that passwords are securely hashed.
- **Login/Logout**: Registered users can log in to their accounts using their credentials. Users can also securely log out, ending their session.

### Real-Time Stock Quotes
- **Lookup**: Users can enter a stock symbol (e.g., AAPL for Apple Inc.) to get the latest stock price using the IEX Cloud API. The website displays the current stock price along with other relevant information.

### Buying and Selling Stocks
- **Buying Stocks**: Users can purchase shares of a stock by entering the stock symbol and the number of shares they wish to buy. The system checks if the user has sufficient funds and updates their portfolio and account balance accordingly.
- **Selling Stocks**: Users can sell shares of a stock they own. They select the stock from their portfolio and specify the number of shares to sell. The system updates their portfolio and adds the proceeds to their account balance.

### Portfolio Management
- **View Portfolio**: Users can view their current portfolio, which displays the stocks they own, the number of shares, the current price of each stock, and the total value of each holding. The portfolio page also shows the user's cash balance.
- **Transaction History**: Users can view a history of their transactions, including all the stocks they have bought and sold, along with the date, price, and number of shares involved in each transaction.

### Account Balance
- **Cash Management**: Users start with a fixed amount of virtual cash that they can use to buy stocks. The website keeps track of the user's cash balance, which is updated with each buy and sell transaction.

### User Interface
- **Intuitive Navigation**: The website is designed with a clean and intuitive interface that makes it easy for users to navigate through different sections such as quoting, buying, selling, and viewing their portfolio.
- **Responsive Design**: The site is designed to be responsive, ensuring a good user experience across different devices and screen sizes.

### Security
- **Password Security**: User passwords are securely hashed to protect user data.
- **Session Management**: The application manages user sessions securely, ensuring that users' data is protected during their interactions with the website.

By providing these features, the Finance website offers a comprehensive platform for users to learn about stock trading and manage a virtual portfolio, all while using real-time data from the stock market.

## Getting Started

### Prerequisites
- Python 3.6 or higher
- Flask
- SQLite
- Jinja2
- Requests
- IEX Cloud API Key
