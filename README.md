# Design Patterns in Java

This project demonstrates the implementation of 10 different design patterns in Java. Each design pattern is implemented in a separate folder with its own classes. Below is a list of the patterns and a brief description of each.

## 1. Strategy Pattern: Payment Processing System
The Strategy Pattern is used to implement a payment system that can handle multiple payment methods (Credit Card, PayPal, Cryptocurrency). You can switch the payment method at runtime.

**Folder**: `StrategyPattern`

## 2. Observer Pattern: Weather Monitoring System
The Observer Pattern is used to create a weather monitoring system. Multiple display devices get updated when the weather data changes.

**Folder**: `ObserverPattern`

## 3. Command Pattern: Remote Control for Smart Home Devices
The Command Pattern is used to design a remote control system for smart home devices (TV, Stereo, Lights). It includes the ability to execute and undo commands.

**Folder**: `CommandPattern`

## 4. State Pattern: Order Processing System
The State Pattern is used for an order processing system that changes its behavior based on the current state of the order (New, Paid, Shipped, Delivered, Cancelled).

**Folder**: `StatePattern`

## 5. Chain of Responsibility Pattern: Expense Approval System
The Chain of Responsibility Pattern is used to handle expense requests through a chain of approvers (Team Lead, Manager, Director, CEO). Each approver can approve up to a certain amount.

**Folder**: `ChainOfResponsibilityPattern`

## 6. Mediator Pattern: Chat Room Application
The Mediator Pattern is used to create a chat room where users can send messages to each other through a central mediator.

**Folder**: `MediatorPattern`

## 7. Memento Pattern: Document Version Control System
The Memento Pattern is used to implement a simple version control system that allows saving and restoring different versions of a document.

**Folder**: `MementoPattern`

## 8. Visitor Pattern: Shape Area Calculator
The Visitor Pattern is used to calculate the area of different shapes (Circle, Rectangle, Triangle). A visitor is used to calculate the area for each shape.

**Folder**: `VisitorPattern`

## 9. Template Method Pattern: Report Generation System
The Template Method Pattern is used to generate reports in different formats (PDF, HTML, Plain Text). The overall process is the same, but the formatting steps are different.

**Folder**: `TemplateMethodPattern`

## 10. Iterator Pattern: Playlist Management System
The Iterator Pattern is used to manage a playlist of songs. It allows traversing the playlist in different orders (Sequential, Shuffle, Genre-based).

**Folder**: `IteratorPattern`

## How to Run the Project

1. Clone the repository or download the code.
2. Open the project in your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Navigate to the `Main.java` class in any of the folders.
4. Run the `Main.java` class to see the pattern in action.

Each folder contains all necessary classes and a `Main.java` file to demonstrate the functionality of the design pattern.

## Requirements
- Java 8 or higher
- A Java IDE or command line

## Conclusion
This project demonstrates the use of 10 popular design patterns. Each pattern solves a specific problem in software design and helps make code more flexible and maintainable.
