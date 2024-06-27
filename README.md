# ATM System Project

This project implements a simple ATM system using Java and MySQL, providing basic banking functionalities such as account creation, accessing accounts, balance enquiries, fund transfers, and account closure.

## Features

- **Creating Account**: Allows users to create new bank accounts with unique account numbers and PINs.
- **Accessing Account**: Enables users to access existing accounts using their account number and PIN to perform various transactions.
- **Balance Enquiry**: Users can check their account balances.
- **Fund Transfer**: Allows transfer of funds between accounts.
- **Account Closure**: Enables users to close their accounts, which deletes their account details from the database.
- **Graphical User Interface (GUI)**: The system uses Java Swing for the GUI, providing a user-friendly interface for interacting with the ATM functionalities.

## Prerequisites

- Java Development Kit (JDK)
- MySQL database
- MySQL Connector/J JDBC driver

## Setup

1. **Database Setup**:
   - Create a MySQL database named `atm`.
   - Execute the SQL script provided (`atm.sql`) to create the necessary table (`CLIENT`) and insert sample data.

2. **Java Setup**:
   - Import the project into your preferred Java IDE (Eclipse, IntelliJ IDEA, etc.).
   - Ensure MySQL Connector/J is added to the project's build path.

3. **Configuration**:
   - Update `jdbc:mysql://localhost:3306/atm` in the Java files with your MySQL database connection details (`username` and `password`).

## Usage

1. Run the `ATM.java` file to start the ATM system GUI.
2. Use the GUI buttons to navigate through different ATM functionalities:
   - Creating Account
   - Accessing Account
   - Balance Enquiry
   - Fund Transfer
   - Account Closure
   - Exit

## Contributors

- [Mayank Kumar](https://github.com/Sun-shINe-arch)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Contact

For questions or suggestions, contact me at [mk7581505@gmail.com].
