# Bankist App
#### This code represents a simple banking application called the "Bankist App." The application allows users to manage their bank accounts, view transactions, transfer money, request loans, and close accounts. Below is a breakdown of the code's main components:

# Data
#### The code defines four account objects, each with attributes such as owner name, transaction movements, interest rate, and a PIN. These accounts are stored in an array called accounts.

# HTML Elements
#### The application interacts with various HTML elements using JavaScript. These elements include labels for displaying information, buttons for user actions (e.g., login, transfer, loan, close account), input fields for user input, and containers for displaying transaction movements.

# Functions
#### displayMovements(movements, sort = false): This function displays transaction movements in the HTML container. If the sort parameter is set to true, it sorts the movements in ascending order.

#### calcDisplayBalance(acc): Calculates and displays the account balance based on the transaction movements.

#### calcDisplaySummary(acc): Calculates and displays the summary of the account, including total income, total outgoing, and earned interest.

#### createUsernames(accs): Generates usernames for each account based on the owner's name.

#### updateUI(acc): Updates the user interface (UI) to display account information, including movements, balance, and summary.

# Event Handlers
#### The code includes event listeners for various buttons and user interactions:

#### btnLogin: Handles the login process by verifying the username and PIN, then displays the account information if successful.

#### btnTransfer: Manages fund transfers between accounts when the user specifies the recipient and amount.

#### btnLoan: Allows users to request a loan if they meet certain criteria.

#### btnClose: Handles account closure by verifying the username and PIN and then removes the account from the accounts array.

#### btnSort: Sorts the transaction movements in ascending or descending order.

#Current Account
#### The currentAccount variable stores the currently logged-in user's account information.

# Overall Functionality
#### The code provides a basic banking app interface, allowing users to perform common banking actions such as viewing transactions, transferring money, requesting loans, and closing accounts.