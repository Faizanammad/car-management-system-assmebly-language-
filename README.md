# car-management-system-assmebly-language-
# Car Management System - 8086 Assembly 🏎️

A console-based **Car Management System** written in 8086 Assembly Language using MASM/TASM.  
This program demonstrates menus, user input handling, conditional logic, counters, and text display in **real-mode DOS**.

---

## Features

- **Main Menu** with options:
  - Today's sales summary
  - Car information display
  - Buy a car
  - Exit program
- **Sales Tracking**:
  - Track total cars sold
  - Track sales per salesman
- **Car Inventory**:
  - Stock tracking for each car model
  - Available colors and prices
- **Purchase Process**:
  - Select salesman, model, color, and price
  - Stock update upon purchase
  - Prints a **receipt** with details
- Clear screen between menus for readability
- Simple **input validation** for menu and selections

---

## Technologies & Concepts

- **8086 Assembly Language**
- DOS interrupts (`int 21h` for I/O)
- Real-mode programming
- Data segment management (`.data`, `.stack`)
- Conditional branching and loops
- ASCII conversions for numeric input/output
- Basic arithmetic and stock tracking

---

## How to Run

1. Open MASM/TASM or DOSBox environment.
2. Assemble and link the code:
   ```asm
   masm car_management.asm;
   link car_management.obj;
