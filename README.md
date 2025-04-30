# Local Produce Store (CSI142 Mini-Project)

This console-based application simulates a simple local produce store using core concepts from CSI142, including Object-Oriented Programming (OOP), Sorting and Searching, Exception Handling, and Version Control.

---

## 🧠 Team Members

- Karabo Zoe Kula — 202406163  
- Bubelebenkosi Nathaniel Dube — 202406089  
- Theo Shawn Thakadu — 202002374  
- Utlwang Utlwang — 202003747  
- Kyle Theo Skosana Masilonyane — 202401193

---

## 🧾 Domain Scenario

The application models a real-world **local produce store**. It manages an inventory of fresh produce items such as fruits and vegetables, allows searching and sorting of items, and includes a shopping cart system for checkout simulation. Custom rules like preventing negative pricing are enforced using custom exceptions.

---

## 🧱 Class Structure

local-produce-store ├── src │ ├── Main.java │ ├── domain │ │ 
├── Product.java 
Defines produce items (name, price, quantity) │ │
├── Inventory.java # Holds a list of available produce items │ │
├── ShoppingCart.java # Simulates a user's shopping cart │ │
├── Sorter.java # Includes sorting and searching methods │ │ 
├── exceptions │ │ │ └── NegativePriceException.java # Custom exception for invalid pricing │ │
└── interfaces │ │ └── Discountable.java # Interface to support future discount features

Compile and run:
javac src/**/Main.java
java Main

Sample output will display:
Initial inventory
Sorted inventory
Search result
Shopping cart and total
