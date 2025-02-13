# School Management System - Grade 12 Computer Science Practical Examination

## Overview

This project is a school management system developed as part of my Grade 12 computer science practical examination.  It was designed to demonstrate understanding of programming concepts, specifically file handling and data structures in C++. The system allows for managing student, teacher, and transport information.  The project was awarded "Outstanding" in the practical examination.

## Features

The school management system includes the following key features:

*   **Student Management:**
    *   Adding new student records
    *   Viewing existing student records
    *   Removing student records
*   **Teacher Management:**
    *   Adding new teacher records
    *   Viewing existing teacher records
    *   Removing teacher records
*   **Transport Management:**
    *   Adding new transport (bus) records
    *   Viewing existing transport records
    *   Removing transport records

## Technology Stack

*   **Programming Language:** C++
*   **Compiler:** Turbo C++ (ideally 3.0 or higher) or Borland C++
*   **Libraries:** Standard C++ Libraries (`iostream.h`, `conio.h`, `dos.h`, `stdlib.h`, `string.h`, `stdio.h`, `process.h`, `fstream.h`, `ctype.h`, `sys/stat.h`, `dir.h`)

## Hardware Requirements (Based on development environment)

The system was developed and tested on the following hardware configuration:

*   Processor: Intel Pentium or equivalent with CPU 3.06 GHz
*   RAM: 4 GB
*   Storage: 40 GB HDD
*   Optical Drive: 52x CDR
*   Video Card: 32m VGA Card

## Software Requirements (Based on development environment)

*   Operating System: Windows 7 or above
*   Compiler: Turbo C++ 3.0 or above / Borland C++

## Project Structure

The project is organized as follows:

*   `comp.pdf`: A PDF document containing the project report, detailing the project's purpose, design, implementation, outputs, and conclusion.
*   `Bus Management System.cpp`: The source code for the entire school management system, written in C++.

The `Bus Management System.cpp` file includes the following key functional sections:

*   **Header and UI Elements:** Functions for creating the user interface, including boxes, lines, and text elements.
*   **Data Structures:**  Structures for managing student (`student`), teacher (`teacher`), and transport (`transport`) data.
*   **Directory Management:** Functions for creating and managing directories to store data files.
*   **Data Handling Functions:** Functions for adding, viewing, and removing records from the data files.
*   **Menu Handlers:**  Functions to present interactive menus for navigating the system.

## Usage Instructions

1.  **Compilation:** Compile the `Bus Management System.cpp` C++ code using Turbo C++ (or Borland C++).
2.  **Execution:** Run the compiled executable.
3.  **Navigation:** Use the arrow keys to navigate the menus.
4.  **Data Entry:** Follow the prompts to enter data for students, teachers, and transport vehicles.

## Key Implementation Details

*   **File Handling:** The system utilizes file handling to store and retrieve data persistently. Each student, teacher, and transport vehicle is associated with a specific data file.
*   **Data Structures:** Structs are used to represent data records for students, teachers and transports.
*   **User Interface:**  A simple text-based user interface is created using functions like `gotoxy`, `puts`, and custom drawing functions (`box`, `line`).
*   **Error Handling:** Basic error handling is implemented to prevent crashes and provide informative messages to the user (e.g. for incorrect inputs and file access problems).
*   **Directory Structure:** It uses `MAIN_DIR`, `STD_DIR`, `TCH_DIR` and `BUS_DIR` to create the necessary folder structure in order to store information

## Limitations

This project was developed as a practical examination and has some limitations:

*   **Limited User Interface:** The user interface is a simple text-based interface.
*   **Basic Error Handling:** Error handling is limited.
*   **No Database Management System:**  Data is stored in simple text files, which lacks the features and robustness of a full database management system.
*   **Vintage Environment:** The code relies on old header files that have been deprecated for some time. Modern compilers might have problems compiling the system.

## Award

This project was awarded "Outstanding" in the Grade 12 computer science practical examination.
