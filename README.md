
# RMI-Based Calculator Application

## Introduction
The RMI-Based Calculator Application is a simple Java project that demonstrates the use of Remote Method Invocation (RMI) for implementing a distributed calculator system. The application allows a client to remotely invoke arithmetic operations on a server.


## Project Objectives
- To understand Java RMI concepts
- To implement remote interfaces and remote objects
- To demonstrate client–server communication
- To perform arithmetic operations remotely


## Features
- Addition of numbers
- Subtraction of numbers
- Multiplication of numbers
- Division of numbers (with error handling)


## Technologies Used
- Programming Language: Java
- Distributed Technology: Java RMI
- IDE: NetBeans
- Java Version: JDK 8 or higher


## Project Structure
RMICalculator
├── src
│ └── calculator
│ ├── Calculator.java
│ ├── CalculatorImpl.java
│ ├── CalculatorServer.java
│ └── CalculatorClient.java
├── README.md
└── nbproject


## Component Description

### Calculator.java
Defines the remote interface and declares the arithmetic methods.

### CalculatorImpl.java
Implements the Calculator interface and provides the logic for arithmetic operations.

### CalculatorServer.java
Starts the RMI registry, creates the remote object, and binds it to the registry.

### CalculatorClient.java
Connects to the remote server, takes user input, invokes remote methods, and displays results.


## How to Run the Project

### Step 1: Start the Server
- Open the project in NetBeans
- Right-click `CalculatorServer.java`
- Select **Run File**
- Output:


### Step 2: Run the Client
- Right-click `CalculatorClient.java`
- Select **Run File**
- Enter two numbers
- Choose an operation
- View the result

> Note: The server must be running before starting the client.

## RMI Communication Flow
1. Client looks up the remote object
2. RMI registry locates the object
3. Client invokes remote methods
4. Server processes the request
5. Result is returned to the client

## Applications
- Academic laboratory exercises
- Learning distributed systems
- Understanding client–server architecture

## Future Enhancements
- Add a graphical user interface (GUI)
- Support multiple clients
- Implement authentication and security
- Deploy on separate machines

## Author
Dawit Eyasu
ugr/34206/16
sec 3/5
CSE
