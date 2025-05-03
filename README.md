# 🍕 Pizza Bill Generator

This is a simple Java application that simulates a pizza billing system. It demonstrates **Object-Oriented Programming (OOP)** principles such as **inheritance**, **encapsulation**, and **method overriding**.

---

## 📌 Features

- Two types of pizzas: **Regular** and **Deluxe**
- Options to:
  - Add **extra cheese**
  - Add **extra toppings**
  - Choose **takeaway**
- Automatic bill generation
- Deluxe pizzas come preloaded with extra cheese and toppings

---

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming (OOP)

---

## 🚀 How to Run

1. Clone or download the repository.
2. Open the project in any Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Run the `Main` class.

---

## 💡 Sample Output

![image](https://github.com/user-attachments/assets/831a58e2-b95a-4adf-892c-e3bc310a4450)


---

## 📘 Code Overview

### `Pizza.java`  
Base class for all pizzas. Handles core logic like:
- Adding cheese
- Adding toppings
- Choosing takeaway
- Generating bill

### `DeluxPizza.java`  
Inherits from `Pizza`. Automatically includes:
- Extra cheese
- Extra toppings

Also overrides methods to prevent duplicate additions.

### `Main.java`  
Entry point of the application. Demonstrates the use of the pizza billing system by:
- Creating regular or deluxe pizza objects
- Calling methods to customize the pizza
- Printing the bill

---

## 🧠 OOP Concepts Demonstrated

- **Encapsulation**  
  - Fields like `price`, `extraCheesePrice` are private and modified via methods.
- **Inheritance**  
  - `DeluxPizza` extends the functionality of `Pizza`.
- **Method Overriding**  
  - In `DeluxPizza`, methods for adding cheese and toppings are overridden to prevent re-adding.

