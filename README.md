# 🌪️ Cyclone Management System (Java)

[![Java](https://img.shields.io/badge/Java-11+-red.svg)](https://www.java.com/)
[![Platform](https://img.shields.io/badge/Platform-Console-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

A console-based application to manage a database of cyclones and classify them by wind speed using **Saffir–Simpson–style hurricane categories**.  
Users can add or update cyclone wind speeds, generate a summary report, clear the database, swap entries, and display the entire dataset.

> **Course:** UTSA · CS1083 · Fall 2023  
> **Author:** Alanna Matundan  

## ✨ Features
- Database initialization (up to 50 cyclone records)  
- Add/Update cyclones with input validation  
- Classification summary by category (Depression → Cat 5)  
- Show all cyclones (index → wind speed)  
- Swap cyclones by index  
- Clear database (reset all speeds)  

## 🧰 Tech Stack
- **Language:** Java (11+ recommended)  
- **I/O:** Scanner for console input  
- **Data Structure:** fixed-size integer arrays  

## 🚀 Getting Started
### Prerequisites
Install Java JDK 11 or newer.  
Check with:
java -version
javac -version


### Compile
javac Cyclone.java


### Run
java Cyclone


## 📖 Usage
When you start, enter how many cyclones (1–50). Then use the menu:
MAIN MENU:
0 - Exit
1 - Add/Update a cyclone
2 - Summary
3 - Clear Database
4 - Show Cyclones
5 - Swap Cyclones


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


## 🧱 Project Structure
Cyclone.java # main program
README.md # documentation


## 📚 What I Learned
- Practiced **input validation** and error handling for user-driven programs  
- Reinforced the use of **arrays** to store and manage structured data  
- Designed a **menu-driven console app** with modular methods  
- Learned to classify real-world data using **conditional logic**  
- Improved ability to think about **data organization and user interaction**


## 🛣️ Future Improvements
- Save/load data from file  
- Handle invalid inputs more gracefully  
- Use a Cyclone class instead of arrays  
- Add sorting, searching, and statistics  
- JUnit tests  


## 📜 License
Educational project. Free to fork & adapt with attribution. 
