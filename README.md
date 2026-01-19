# 🛠️ Tormenta20 Vendor Management System

## 📌 Introduction

This project was developed to **deepen my understanding of Java**. After completing a course on the language, I wanted to apply the knowledge I gained in a practical project while also exploring concepts beyond the course material.

Additionally, this project was designed to **assist Tormenta20 game masters** by helping them create vendors for their campaigns, streamlining gameplay and enriching the overall gaming experience.

---

## 💻 Technologies Used

**Java**: The project is fully developed in Java, leveraging **Object-Oriented Programming (OOP)** principles.

---

## ⚙️ Key Features & Resources

### 🔹 Control Structures

* `if`, `else`, `switch-case` → manage program flow
* `while(true)` → create loops that run until a specific exit condition is met

### 🔹 Exception Handling

* `try-catch` blocks handle input errors, such as `InputMismatchException`, ensuring the program doesn’t crash if the user enters invalid data

### 🔹 Input & Output

* `Scanner` → read user input from the console
* `System.out.print` / `System.out.println` → display messages in the console

### 🔹 Collections

* `ArrayList<Vendedores>` → dynamically store the list of vendors

### 🔹 Object-Oriented Programming (OOP)

* **Custom Classes**: `Vendedores`, `EspadasDeUmaMão`, `EspadaDeDuasMãos`, `ArmaduraPesada`, `ArmadurasLeves`
* **Objects**: Each vendor and item is an instance of its respective class
* **Encapsulation**: Getters (`getnome()`, `getSaldoDoVendedor()`) and methods (`AdicionarItens()`, `debitarSaldo()`) manipulate object data safely

### 🔹 Input Validation

* Utility methods `LerInt()` and `LerDouble()` ensure valid numeric input
* Friendly error messages guide the user when invalid input is entered

### 🔹 Interactive Menu

* Console-based menu for creating vendors, adding items, and simulating sales
* State management using **boolean flags** controls menu navigation

---

## 👤 User Capabilities

Users can interact with the system in the following ways:

### 1️⃣ Create Vendors

* Add vendors by specifying their **name** and **account balance**

### 2️⃣ Add Items to Vendors

* Items can be added to a vendor’s inventory
* Current categories:

  * **Weapons**: One-handed swords, two-handed swords
  * **Armor**: Light armor, heavy armor

### 3️⃣ Access Vendors

* View existing vendors and select one to interact with
* Access a vendor’s **inventory** to see their items

### 4️⃣ Sell Items to Vendors

* Sell items to a selected vendor, provided they have sufficient balance

> This system provides an **interactive, console-based way** to manage vendors and their inventories, simulating a simplified RPG marketplace.

---

## ⌨️ Keyboard Shortcuts

* All shortcuts are displayed when the program is running
* Users receive clear instructions on what actions they can perform

---

## 🚀 How to Run

1. Use an IDE like **IntelliJ IDEA**
2. Ensure **Java JDK 17** is installed on your system
3. Run the `App` class to start the program

---

## 🎓 What I Learned

This project helped me **strengthen my Java skills**, including:

* Object-oriented programming (OOP)
* Boolean values and conditional logic
* Lists and variable manipulation

> It was an excellent opportunity to consolidate my programming knowledge and apply theory in a **practical, hands-on project**.

---

## 🌟 Future Improvements

Planned enhancements include:

* Implementing a **purchase system** for vendors
* Expanding the **variety of items** available for each vendor
* Introducing **different vendor classes** (e.g., blacksmiths, carpenters, hunters, butchers) to make the system more dynamic and engaging
