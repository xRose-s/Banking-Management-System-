<!-- # 🏦 ATM Management System

An ATM Management System implemented in Java with a graphical user interface using JSwing and AWT libraries. This project simulates an ATM interface, allowing users to sign up, log in, and perform various banking transactions.

## 🚀 Features

- **User Authentication**
  - Sign up with personal details
  - Secure login with card number and PIN

- **Banking Operations**
  - Deposit
  - Cash withdrawal
  - Fast Cash    
  - Mini Statement
  - Pin Change
  - Balance Enquiry

- **Database Integration**
  - MySQL database for storing user details and transaction history

## 🖼 Screenshots

| Sign Up Form | ATM Dashboard | Transaction History |
|--------------|---------------|---------------------|
| ![Sign Up Form](images/signup.png) | ![ATM Dashboard](images/dashboard.png) | ![Transaction History](images/transactions.png) |

## 🛠 Technology Stack

- **Java**: Core application logic
- **JSwing and AWT**: GUI components
- **MySQL**: Database for user and transaction data

## 📁 Project Structure

```
ATM-Management-System/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/atm/
│   │   │   │   ├── ATM.java          // Main application
│   │   │   │   ├── Login.java        // Login screen
│   │   │   │   ├── SignUp.java       // Sign up form
│   │   │   │   ├── Dashboard.java    // ATM dashboard
│   │   │   │   ├── Transaction.java  // Transaction processing
│   │   └── resources/
│   │       ├── images/               // UI images
│   │       ├── sql/                  // SQL scripts for database setup
│   ├── test/                         // Unit tests
```



## ⚙️ Setup and Installation

   ```

. **Database Setup:**
   - Import the provided SQL scripts in the `src/main/resources/sql/` directory into your MySQL database to create the necessary tables.

. **Run the Application:**
   - Compile the Java code and run the `ATM.java` main class.

## 📝 Usage

1. **Sign Up:**
   - New users can sign up by providing personal details across three forms.
   - Details include name, address, contact information, and initial deposit.

2. **Login:**
   - Use the card number and PIN provided during the sign-up process to log in.

3. **Banking Operations:**
   - Once logged in, users can perform various transactions like balance inquiry, cash withdrawal, and more.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



