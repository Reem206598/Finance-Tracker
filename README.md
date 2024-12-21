# Personal Finance Tracker

A simple React-based Personal Finance Tracker app that helps users manage their incomes and expenses. The app allows users to add, view, and manage their financial transactions in real-time.

## Features

- **Track Income and Expenses**: Add transactions as income (positive) or expenses (negative) and see your balance in real-time.
- **Responsive Design**: The app is responsive and looks great on all devices.
- **Transaction History**: View a list of all transactions with details.
- **Easy-to-Use Interface**: Simple, user-friendly interface for adding and managing transactions.

## Technology Used

- **React**: A JavaScript library for building user interfaces.
- **CSS**: Custom styles to make the application visually appealing.
- **Context API**: For global state management to manage transactions across different components.
- **JavaScript**: Core language for the functionality.

## Installation

To run this project locally, follow the steps below:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/personal-finance-tracker.git
```

### 2. Navigate to the Project Folder

```bash
cd personal-finance-tracker
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm start
```

Visit `http://localhost:3000` in your browser to view the app.

## Usage

- You can add transactions by filling in the description and amount fields.
- Positive amounts are considered income, and negative amounts are considered expenses.
- The app will automatically update the balance as transactions are added.
- View the history of transactions listed below the form.

## Components

- **Header**: Displays the title and overall balance.
- **Balance**: Displays the current balance, showing total income and total expenses.
- **IncomeExpenses**: Shows the total income and expenses.
- **TransactionList**: Displays a list of all transactions.
- **AddTransaction**: Allows users to add new transactions.

## Contributing

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is open-source and available under the MIT License.
