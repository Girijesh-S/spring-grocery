# 🛒 SpringGrocery - Organic Store (Java Console App)

Welcome to **SpringGrocery**, a console-based organic store application built in Java. 
This app simulates a home delivery system where customers can place orders for organic products and view billing and delivery details.

---

## 🌟 Features

### 🧑 User Registration
- Collects customer details including name, phone, address, and delivery date.
- Validates phone numbers, pin codes, and city selection.
- Supports delivery to:
  - Chennai
  - Chengalpattu
  - Kancheepuram

### 🛍️ Product Catalog
- Organized into multiple categories:
  - Fruits
  - Vegetables
  - Rice & Cereals
  - Oils & Ghee
- Supports quantity selection: `0.25`, `0.5`, or `1.0` kg/litre.
- Displays stock and dynamically updates based on orders.

### 🛒 Order & Cart
- Allows customers to browse products and add items to the cart.
- Maintains real-time stock availability.
- Automatically calculates total and checks for **free delivery** (orders above ₹500).

### 🧾 Billing & Delivery Summary
- Displays a detailed bill summary of items ordered with pricing.
- Shows delivery details including address and chosen delivery date.

---

## 🏗️ Tech Stack

- **Language**: Java
- **Interface**: Console-based (No GUI)
- **Collections Used**: `List`, `ArrayList`, etc.

---

## 🚀 How to Run the App

### ✅ Requirements

- Java 8 or above
- Any IDE (IntelliJ, Eclipse) or terminal with `javac`

### 🔧 Steps to Compile and Run

1. Clone or download the project.
2. Ensure the following files are in the same directory:
   - `Main.java`
   - `Category.java`
   - `Item.java`
   - `OrderItem.java`
   - `UserDetails.java`
3. Compile the program using PowerShell or terminal:

   ```PowerShell
   javac Main.java Category.java Item.java OrderItem.java UserDetails.java
4. Run the Program

   ```PowerShell
   java Main.java
   
