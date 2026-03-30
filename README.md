Fiza Rasool
FA25-BCS-030
section :C
LAB TASK 2
Task: Account → SavingsAccount → PremiumSavingsAccount

Project Overview
This project implements a banking system using Multilevel Inheritance in Java. It demonstrates core OOP concepts including constructor chaining, method overriding, and the use of access modifiers.

Class Hierarchy
Account (Base Class): Contains accountNumber and balance. Includes methods for deposit() and withdraw().

SavingsAccount (Intermediate Class): Inherits from Account. Adds interestRate and minimumBalance.

PremiumSavingsAccount (Derived Class): Inherits from SavingsAccount. Adds rewardPoints and freeTransactions.

Implementation Highlights
Access Modifiers: All attributes are declared as protected as per requirements.

Constructor Chaining: Uses super() to pass data up the inheritance chain.

Method Overriding: Both display() and toString() are overridden in every class to provide specific object details.

Demo Class: Demo.java creates objects of all three levels and calls their respective methods to demonstrate functionality.

