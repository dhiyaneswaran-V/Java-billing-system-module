# Java Billing System

This Java program represents a simple billing system that allows owners and cashiers to manage stock, create bills, and perform various operations. Below is a brief guide on how to use and understand the functionality of the code.

## Table of Contents

1. [Overview](#overview)
2. [Classes](#classes)
3. [Usage](#usage)
4. [Owner Operations](#owner-operations)
5. [Cashier Operations](#cashier-operations)
6. [Exit](#exit)

## Overview

The billing system consists of three main classes: `Bill`, `Product`, and `Cashier`. The `Main` class contains the main method to run the program. It allows owners to view reports, add cashiers, and perform other relevant operations.

## Classes

### Bill Class

- Represents a bill with attributes: product name (`pname`), quantity (`qt`), and amount (`amt`).
- Provides methods to set bill details (`setall`) and display the bill (`show`).

### Product Class

- Represents a product with attributes: product name (`pname`), price (`pr`), product ID (`id`), quantity (`qt`), and amount (`amt`).
- Provides methods to set product details (`setall`), display product details (`show`), check product name (`check`), and get product price (`getprice`).

### Cashier Class

- Represents a cashier with attributes: cashier ID (`id`), password (`pw`), list of products (`p`), and list of bills (`b`).
- Provides methods to set cashier details (`ch`), check login credentials (`check`), add products (`setpro`), add bills (`setbill`), and display products and bills (`showproduct` and `showbill`).

### Main Class

- Contains the `main` method to run the program.
- Manages the interaction with owners and cashiers.

## Usage

1. Run the program.
2. Choose the user type: Owner, Cashier, or Exit.

## Owner Operations

### 1. Add Cashier

- Enter the owner ID and create a password.
- Choose to add a new cashier by entering their ID and creating a password.

### 2. Report

- View reports on stock and bills.
  - Choose "Stock" to view the list of products.
  - Choose "Bill" to view the list of bills.

### 3. Exit

- Exit the owner operations and return to the main menu.

## Cashier Operations

### 1. Stock Entry

- Add a new product to the stock by providing the product name, ID, price, and quantity.

### 2. Bill Entry

- Create a bill by entering the quantity and product name.
- The program calculates the total amount based on the product price and quantity.

### 3. Exit

- Exit the cashier operations and return to the main menu.

## Exit

- Terminate the program.

Feel free to explore and modify the code to suit your specific requirements.
