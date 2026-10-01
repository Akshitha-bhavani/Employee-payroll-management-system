
---

# Employee Payroll Management System

**Repository:** `employee-payroll-management-system`

Your code currently has `public class Main`, so upload the source file as **`Main.java`**. The program creates Permanent, Contract, and Part-Time employees and calculates their salaries through overridden methods. :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}

Copy this into the repository's `README.md`:

```markdown
# Employee Payroll Management System

A Java-based employee payroll management system developed to demonstrate object-oriented programming concepts such as inheritance and method overriding.

## Overview

This project manages employee information and calculates salaries for different types of employees.

The system demonstrates how a common Employee class can be extended to create different employee categories with their own salary calculation methods.

## Technologies Used

- Java
- Object-Oriented Programming

## Employee Types

The system supports:

- Permanent Employee
- Contract Employee
- Part-Time Employee

## Features

- Employee ID management
- Employee name management
- Basic salary management
- Salary calculation
- Employee detail display
- Different salary calculations for different employee types

## OOP Concepts Demonstrated

### Inheritance

The employee categories inherit common properties and methods from the base `Employee` class.

### Method Overriding

Each employee type provides its own implementation of the `calculateSalary()` method.

### Classes and Objects

The project uses classes and objects to represent employees and their payroll information.

### Polymorphism

Employee references are used to work with different employee types while invoking their respective salary calculation methods.

## Salary Calculation

### Permanent Employee

```text
Salary = Basic Salary + Allowance - Deduction
