# library-Management
Here is a clean, well-structured **README.md** based on your uploaded Python script **Library mangement.py** .

---

# 📚 Library Management System

A simple command-line based Library Management System built in Python.
This script allows users to choose whether they want to browse available books, and opens relevant learning resources in their web browser.

---

## 🚀 Features

* Simple and interactive command-line interface
* Lets the user choose between exiting or browsing books
* Displays a list of four programming books
* Opens the selected book's reference link in the default web browser
* Handles invalid inputs gracefully

---

## 📄 How It Works

1. When the script starts, the user is asked to enter:

   * `0` → Exit the system
   * `1` → View and select books

2. If the user chooses to view books, the script displays:

   * Book 1 – C
   * Book 2 – Java
   * Book 3 – HTML
   * Book 4 – Python

3. Upon selecting a book, the corresponding link opens automatically:

   * C → GeeksforGeeks
   * Java → W3Schools
   * HTML → W3Schools
   * Python → W3Schools

4. Program ends with a thank-you message.

---

## 🧩 Code Structure

### **Functions**

#### `run(b)`

* Handles the main menu input (`0` or `1`)
* Navigates to the book list if user enters `1`
* Ends the program if user enters `0`

#### `book(a)`

* Takes the book number as input
* Opens the relevant resource URL
* Displays an invalid message if the number doesn't match any book

---

## ▶️ Running the Program

Make sure you have Python installed.
Run the script using:

```bash
python "Library mangement.py"
```

---

## 🔗 External Resources Used

The script opens the following educational sites:

* GeeksforGeeks
* W3Schools

These serve as learning resources for selected programming topics.

---

## ✔️ Requirements

* Python 3.x
* Internet connection (for opening book resources)

---

Just tell me!
