# Car-sales-app
# 🚗 Car Sales Management System

### A simple console-based C program for managing a car dealership.

---

## 🧠 What This Project Is

This project is a **Car Sales Management** System built in **C**.
It was created for a university assignment, but it’s also a fun little simulation of how a small car dealership might handle their sales, stock, and customer feedback.

The program runs entirely in the console and lets you:

* Check what cars are in stock
* Buy cars
* See overall sales data
* Leave customer feedback

It’s also a great example of working with arrays, files, and data validation in C.

---

## 🔧 Features

### 🌀 Main Menu

* Loops until the user exits.
* Four main options:

  1. View Car Stock
  2. Buy Cars
  3. View Sales Data
  4. Customer Feedback
* Validates input so the program won’t crash if you type something weird.

### 🚘 Car Stock

* Stores car details in arrays:

  * Price
  * Model
  * Year
  * Amount in stock
* The list is **sorted by year (newest first)** when displayed.

### 💰 Buying Cars

* Lets a customer purchase one or more cars.
* Records:

  * Customer name and age
  * Date of purchase
  * How many cars were bought
  * Total price
  * Discounts (if applicable)
* Updates stock after each sale.
* Makes sure all user input is valid before continuing.

### 📊 Sales Data

* Shows a breakdown of all sales, including:

  * Total cars sold per model
  * Total sales value per model
* Sorted by total sale amount (highest first).
* Sales data is **saved to a file** and automatically **loaded when the program starts**, so you don’t lose your data between runs.

### 💬 Customer Feedback

* After buying, the customer can leave a short comment and rating out of 5.
* Feedback is saved and linked to the car model.

### 🧩 Bonus / Advanced Features

* Uses **dynamic memory allocation** to handle flexible data.
* Optional **file encryption** for protecting saved data.
* Organized and readable code following good C programming practices.

---

## ⚙️ How to Run

### Requirements

* Any C compiler (e.g. GCC)
* Command line access (macOS, Linux, or Windows)

### Compile

```bash
gcc car_sales_project.c -o car_sales
```

### Run

```bash
./car_sales
```

When you run it, it will create or load:

* `sales_data.txt` – stores all your sales
* `feedback.txt` – (optional) stores customer feedback

---

## 🖥️ Example

```
===== CAR SALES MANAGEMENT SYSTEM =====
1. View Cars Stock
2. Buy Cars
3. View Sales Data
4. Customer Feedback
5. Exit
Enter your choice: 1

Available Cars:
Model: BMW 3 Series | Year: 2022 | Price: £25000 | Stock: 5
Model: Mercedes C-Class | Year: 2021 | Price: £27000 | Stock: 3
```

---

## ✍️ About

Created by **[Your Name]**
Student ID: [Your Student ID]
Module: [Your Module Name or Code]
Year: 2025

I built this to practice:

* Working with arrays and loops
* Reading/writing files
* Validating user input
* Sorting data
* Structuring a small project in C
---

Would you like me to make it sound even more “personal” (like a dev portfolio project on GitHub), or keep this balance between friendly and academic?
