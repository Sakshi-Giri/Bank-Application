
# Basic Bank Application

This is a basic bank application implemented in Java. It allows users to create a bank account, deposit and withdraw money, update account details, and check their balance.

## Features

- **Create Account**: Users can create a new bank account by providing their details such as name, address, Aadhar number, PAN number, PIN, initial balance, and phone number.
- **Existing User**: Existing users can log in to their account using their PIN and perform various operations:
  - Check balance
  - Deposit money (to deposite money it need PIN)
  - Withdraw money  (to withdraw money it need PIN)
  - Update account details (name, address, PIN, phone number)
  - **Display Account**: Users can view their account details.
 
## Concepts Used

The following concepts of Java programming are utilized in this application:

- **Classes and Objects :** The application is structured using classes and objects to represent bank accounts and the bank itself. 
- **Encapsulation :** Private variables (account, scanner) and methods are used to encapsulate the internal state and behavior of the classes.
- **Methods :** Various methods are implemented to perform actions like deposit, withdraw, update account details, etc.
- **User Input Handling :** The Scanner class is used to handle user input for creating accounts and performing operations.
- **Control Structures (Loops) :** while loops are used to provide continuous options for updating account details and performing operations.
- **Switch Statements :** Switch statements are used to handle different user options.
- **Getter and Setter Methods :** Getter and setter methods are used to access and modify private variables (account, scanner) in a controlled manner.
- **Conditional Statements :** Conditional statements are used to verify PINs and check for sufficient balance.
  
## Getting Started

### Prerequisites
- Java Development Kit (JDK) installed on your system
- Git (optional) for cloning the repository

### Installation
1. Clone this repository to your local machine:

   ```
   git clone https://github.com/your-username/basic-bank-application.git
   ```

   Alternatively, you can download the repository as a ZIP file and extract it.

2. Navigate to the project directory:

   ```
   cd basic-bank-application
   ```

3. Compile the Java files:

   ```
   javac BankApplication.java
   ```

### Usage
1. Run the compiled Java program:

   ```
   java BankApplication
   ```

2. Follow the on-screen instructions to use the bank application.
