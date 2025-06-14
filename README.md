# Bankist App

This project is a fully functional banking application built with **vanilla JavaScript**, HTML, and CSS. It simulates a real-world banking interface where users can log in, view their transactions, transfer money, request loans, and close their accounts. The app also features internationalization and currency formatting based on user locale.

---

LINK :  https://pawelni123.github.io/Bankist-app/
## Features

- **User Authentication**  
  Secure login with username and PIN.
TO LOG IN use: username: js and PIN: 1111

- **Account Overview**  
  Displays current balance, transaction history, and summary of money in, out, and interest earned.

- **Transaction Management**  
  - **Money Transfers:** Users can transfer money to other accounts.  
  - **Loan Requests:** Users can request loans that get approved based on certain criteria.  
  - **Account Closure:** Users can close their account after confirming their credentials.

- **Sorting Transactions**  
  Sort transaction movements by amount in ascending or descending order for better overview.

- **Localized Dates and Currency Formatting**  
  - Dates are formatted dynamically (e.g., "Today", "Yesterday", or specific dates) using `Intl.DateTimeFormat` and custom logic.  
  - Currency values are displayed according to the user's locale and currency with `Intl.NumberFormat`.

- **Auto Logout Timer**  
  For security, users get logged out automatically after a period of inactivity, with a visible countdown timer.

---

## What I Learned

By building the Bankist app, I enhanced my skills in:

### JavaScript & DOM Manipulation

- Working with **event listeners** and **form inputs** to create an interactive UI.  
- Dynamically rendering HTML based on data, manipulating the DOM effectively.  
- Applying **array methods** (`map`, `filter`, `reduce`, `find`, `some`) to process banking data and implement features such as sorting and validating transactions.  
- Using **dates and internationalization APIs** (`Intl.DateTimeFormat` and `Intl.NumberFormat`) for formatting transaction dates and currencies appropriately based on user locale.  
- Implementing logic for **realistic banking rules**, such as loan approval only if the user has sufficient deposit history.

### Application Architecture & UX

- Managing **application state** through JavaScript objects representing accounts, transactions, and user sessions.  
- Creating **secure authentication** flows with PIN verification and input validation.  
- Designing a **clean and user-friendly interface** using semantic HTML and CSS, with responsive and accessible form inputs.  
- Implementing an **auto logout timer** that resets on user activity to enhance security.

### Real-World Banking Concepts

- Simulating deposits, withdrawals, and transfer operations.  
- Handling loan requests with delays to mimic real-life processing time.  
- Managing multiple user accounts with different currencies and locales.  

---

## Project Structure

- `index.html` — Main HTML file containing the app structure and UI elements.  
- `style.css` — Stylesheet with responsive, modern styling for the application.  
- `script.js` — JavaScript logic managing data, UI updates, event handling, and app functionality.

---

