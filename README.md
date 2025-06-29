# Bank Management System (Java Applet)

This project is a Bank Management System implemented using Java Applets. It provides a graphical user interface for basic banking operations such as login, balance enquiry, deposit, withdrawal, fast cash, mini statement, and account signup. The system connects to a MySQL database for data storage and retrieval.

## Features

- User login and authentication
- Account signup (multi-step)
- Balance enquiry
- Deposit and withdrawal
- Fast cash options
- Mini statement
- PIN management

## Project Structure

```
bank management system/
├── bank management system.iml
├── jcalendar-tz-1.3.3-4.jar           # Calendar library
├── mysql-connector-java-8.0.28.jar    # MySQL JDBC driver
├── src/
│   ├── Main.java                      # Main entry point
│   └── bank/management/system/
│       ├── login.java
│       ├── Signup.java
│       ├── Signup2.java
│       ├── Signup3.java
│       ├── BalanceEnquriy.java
│       ├── Deposit.java
│       ├── Withdrawl.java
│       ├── FastCash.java
│       ├── mini.java
│       ├── Pin.java
│       ├── main_Class.java
│       └── _on.java
├── icon/
│   ├── atm2.png
│   ├── backbg.png
│   ├── bank.png
│   ├── card.png
│   └── provider.png
```

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL Server
- The following JARs in your classpath:
  - `mysql-connector-java-8.0.28.jar`
  - `jcalendar-tz-1.3.3-4.jar`

## Setup & Running

1. Clone or download this repository.
2. Set up the MySQL database and update connection details in the source code if needed.
3. Compile the Java source files:
   ```sh
   javac -cp ".;mysql-connector-java-8.0.28.jar;jcalendar-tz-1.3.3-4.jar" src/Main.java
   ```
4. Run the application:
   ```sh
   java -cp ".;src;mysql-connector-java-8.0.28.jar;jcalendar-tz-1.3.3-4.jar" Main
   ```

## Notes

- Ensure the MySQL server is running and accessible.
- Update database credentials in the code as per your setup.
- The UI uses images from the `icon/` directory.

## License

This project is for educational purposes.
