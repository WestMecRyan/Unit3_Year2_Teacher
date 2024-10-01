# Trust US Bank

## **Banking Website**

### **Project Description**
Create a secure banking web application where users can create accounts, log in, and perform transactions such as deposits and withdrawals. Users can view their transaction history and account balance.

### **Key Features**
- **User Authentication:**
  - Secure sign-up, login, and logout functionalities.
- **Account Management:**
  - View account details and current balance.
- **Transactions:**
  - Deposit funds into the account.
  - Withdraw funds from the account with balance checks.
- **Transaction History:**
  - Display a log of all deposits and withdrawals.
- **Profile Management:**
  - Allow users to update their personal information.

### **Technical Requirements**
- **Frontend:**
  - Clean and intuitive UI using HTML and CSS.
  - Forms for registration, login, deposits, withdrawals, and profile updates.
  - Client-side validation with JavaScript regex for inputs like account numbers, amounts, email formats, etc.
- **Backend:**
  - Express.js server with RESTful API endpoints for all functionalities.
  - JSON file storage to manage user data and transaction records using the `fs` module.
  - Implement session management or token-based authentication for security.
- **Asynchronous Operations:**
  - Use `async/await` for handling fetch requests and file operations.
- **Additional Features:**
  - Ensure secure handling of sensitive data (password hashing recommended).
  - Implement error handling for invalid transactions (e.g., insufficient funds).

### **Project Milestones**
1. **Setup and Authentication:**
   - Initialize the project and implement secure user registration and login.
2. **Account Features:**
   - Develop account overview and balance display.
3. **Transaction Handling:**
   - Implement deposit and withdrawal functionalities with validation.
4. **Transaction History:**
   - Create a transaction log view for users.
5. **Final Enhancements:**
   - Refine UI, ensure security measures, perform testing, and prepare for presentation.

---