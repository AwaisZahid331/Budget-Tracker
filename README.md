Budget Tracker Full-Stack Application

This is a full-stack budget tracking application designed to help users manage their income and expenses efficiently. The project uses the MERN stack (MongoDB, Express.js, React.js, Node.js) and is hosted live using GitHub and Vercel.

##Features

Add Transactions: Categorize transactions as either income or expenses.

View Transactions: Display a list of all transactions with details like title, amount, category, and type.

Delete Transactions: Remove unwanted transactions easily.

Track Balance: View total income, expenses, and the current balance.

Responsive Design: Works on desktop, tablet, and mobile devices.

Tech Stack

Frontend

React.js: Dynamic user interface.

Bootstrap: Responsive and styled components.

Backend

Node.js: Server-side environment.

Express.js: Backend framework for routing and APIs.

Database

MongoDB: Stores transaction data.

Hosting

GitHub: Code repository.

Vercel: Live hosting of the frontend.

Installation and Setup

Prerequisites

Node.js and npm installed on your system.

MongoDB database (local or cloud).

Steps

Clone the repository:

git clone https://github.com/<your-username>/Budget-Tracker.git
cd Budget-Tracker

Install dependencies for both client and server:

cd client
npm install
cd ../server
npm install

Create an .env file in the server directory and add:

MONGO_URI=<your-mongodb-connection-string>
PORT=5000

Start the application:

Backend: npm start (from server directory)

Frontend: npm start (from client directory)

Access the app at http://localhost:3000.

APIs Used

Transactions API

POST /transactions - Add a transaction.

GET /transactions - Fetch all transactions.

DELETE /transactions/:id - Delete a transaction.

Example Usage

Adding a Transaction:

Title

Amount

Category

Type

Shopping

2000

Personal

Expense

Freelancing

5000

Work

Income

Display:

Balance: Automatically calculates total income and expenses.

Live Demo

Click here to view the app

Screenshots

Home Page


Add Transaction Form


Transaction List


Future Improvements

Implement user authentication.

Add transaction filtering and search functionality.

Generate reports and graphs for better analysis.

Contributing

Feel free to fork the repository and submit pull requests with improvements or bug fixes.

License

This project is open-source and available under the MIT License.

