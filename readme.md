# Expense Tracker Documentation
# Author: Carlos Alberto Guzmán

## Overview

This Expense Tracker is a simple web application for managing your budget and expenses. It allows you to set a budget, add expenses, and view a list of your expenses. The application also provides the functionality to edit and delete expenses.

## Code Structure

### Variables
- `budget`: Input element for entering the budget.
- `nameExpensive`: Input element for entering the name of the expense.
- `expenseAmount`: Input element for entering the amount of the expense.
- `expensive_total`: Display element for the total budget.
- `budgetElement`: Display element for the budget.
- `balanceElement`: Display element for the remaining balance.
- `expenseName`: Display element for the name of the expense.
- `headerElement`: HTML header element.
- `total`: Variable to store the total budget.
- `balance`: Variable to store the remaining balance.
- `uniqueId`: Variable for generating unique IDs.
- `editing`: Flag to indicate whether an expense is being edited.
- `expenseObject`: Object to store details of an expense.
- `expenseList`: Array to store a list of expenses.

### Buttons
- `btnCreateBudget`: Button for creating the budget.
- `btnAddExpensive`: Button for adding an expense.

### Error Elements
- `alertElement`: HTML element for displaying alerts.
- `alertErrorEl`: HTML element for displaying error messages.

## Functions

### `messageHandler(message, type, cascade)`

This function handles displaying messages and alerts on the UI.

- `message`: The message to be displayed.
- `type`: The type of message (e.g., "success", "danger").
- `cascade`: Optional parameter to determine if the alert should cascade.

### `createBudget()`

This function creates the budget based on the user input.

### `idGenerator()`

This function generates a unique ID for expenses.

### `addExpensive()`

This function adds an expense to the list and updates the UI.

### `resetValues()`

This function resets input values.

### `renderHTML(data, id)`

This function renders HTML content on the UI.

### `deleteData(e)`

This function deletes an expense from the list.

### `saveIntoLocalStorage(key, value)`

This function saves data into local storage.

### `showFromLocalStorage(key)`

This function retrieves data from local storage and displays it on the UI.

### `prepareEdition(e)`

This function prepares the UI for editing an expense.

### `editData(id)`

This function edits an expense and updates the UI.

## Event Listeners

- `btnCreateBudget`: Event listener for the "Create Budget" button.
- `btnAddExpensive`: Event listener for the "Add Expense" button.
- `DOMContentLoaded`: Event listener for when the DOM has fully loaded.

## Additional Features

- The application supports scrolling, and a fixed header is added when the user scrolls down.

Feel free to customize and extend the documentation based on additional details or features in your code.
