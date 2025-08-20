# 🌪️ Cyclone Management System (Java)

[![Java](https://img.shields.io/badge/Java-11+-red.svg)](https://www.java.com/)
[![Platform](https://img.shields.io/badge/Platform-Console-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

A console-based program to manage a database of cyclones and classify them by wind speed using **Saffir–Simpson–style hurricane categories**.  
Users can add or update cyclone data, generate classification summaries, clear the database, swap entries, and display all records.  

> **Course:** UTSA · CS1083 · Fall 2023  
> **Author:** Alanna Matundan  

---

## ✨ Features
- Initialize a database of up to 50 cyclone records  
- Add or update cyclone wind speeds with input validation  
- Generate classification summaries (Depression → Category 5)  
- Display all cyclone records (index → wind speed)  
- Swap cyclone entries by index  
- Clear the database (reset all speeds)  

---

## 🧰 Tech Stack
- **Language:** Java (11+ recommended)  
- **I/O:** Scanner (console input)  
- **Data Structure:** Fixed-size integer arrays  

---

## 🚀 Getting Started
### Prerequisites
Install Java JDK 11 or newer. Check your version:  
java -version
javac -version

shell
Copy
Edit

### Compile
javac Cyclone.java

shell
Copy
Edit

### Run
java Cyclone

yaml
Copy
Edit

---

## 📖 Usage
When launched, the program asks for the number of cyclones (1–50).  
Users interact with the following menu:  

MAIN MENU:
0 - Exit
1 - Add/Update a cyclone
2 - Summary
3 - Clear Database
4 - Show Cyclones
5 - Swap Cyclones

shell
Copy
Edit

### Example
Please, enter the number of cyclones in the database (Max 50): 5
Select an option: 1
Enter the index (0 to 4): 0
Enter the new wind speed (0 - 1000): 82
Select an option: 2
Cyclones’ Classification Summary
Tropical Depression: 0
Tropical Storm: 0
Hurricane Category 1: 1
Hurricane Category 2: 0
Hurricane Category 3: 0
Hurricane Category 4: 0
Hurricane Category 5: 0

yaml
Copy
Edit

---

## 🧱 Project Structure
Cyclone.java # main program
README.md # documentation

yaml
Copy
Edit

---

## 📚 What I Learned
- Implemented **input validation** and error handling for console apps  
- Practiced using **arrays** to manage structured datasets  
- Built a **menu-driven interface** with modular methods  
- Classified real-world data through **conditional logic**  
- Strengthened skills in **data organization and user interaction**  

---

## 🛣️ Future Improvements
- Add save/load functionality to persist data  
- Improve handling of invalid input cases  
- Replace arrays with a **Cyclone class** and dynamic structures  
- Add sorting, searching, and statistical reports  
- Implement unit testing with **JUnit**  

---

## 📜 License
Educational project — free to fork, adapt, and extend with attribution. 
