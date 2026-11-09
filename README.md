# 🏨 Hotel Management System

A desktop-based **Hotel Management System** built with **Java Swing GUI**, developed as a CSE215 (Java Programming) course project. It provides a simple graphical interface for handling core hotel operations such as rooms, guests, bookings, and billing.

![Java](https://img.shields.io/badge/Language-Java-orange)
![GUI](https://img.shields.io/badge/GUI-Swing-blue)
![Type](https://img.shields.io/badge/Type-Desktop%20App-green)
![Course](https://img.shields.io/badge/Course-CSE215-purple)

---

## 📑 Table of Contents
1. [Overview](#-overview)
2. [Features](#-features)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#-project-structure)
5. [Prerequisites](#-prerequisites)
6. [Installation & Setup](#installation--setup)
7. [How to Run](#how-to-run)
8. [How to Use](#how-to-use)
9. [Object-Oriented Concepts Used](#-object-oriented-concepts-used)
10. [Future Improvements](#-future-improvements)
11. [Contributing](#-contributing)
12. [Author](#author)
13. [License](#-license)

---

## 📖 Overview
Managing a hotel manually is slow and error-prone. This project digitizes the main hotel workflow in one desktop application with an easy-to-use Swing interface. Hotel staff can manage rooms, register guests, handle bookings, and generate bills from a single window.

**Objectives**
- Apply Java OOP concepts in a real-world application
- Build a user-friendly GUI using Java Swing
- Reduce manual record keeping in hotel management

---

## ✨ Features
- 🔐 **Login system** for authorized staff/admin
- 🛏️ **Room management**: add, view, update, and delete rooms
- 👤 **Guest management**: register and view guest details
- 📅 **Room booking**: reserve available rooms
- ✅ **Check-in / Check-out** handling
- 💳 **Billing**: calculate and display total charges
- 🔍 **Search & view records** for rooms and guests
- 🖥️ Clean, event-driven **Swing GUI**

> Features depend on the implemented classes. Remove any that are not in your code.

---

## Technologies Used
| Category | Technology |
|---|---|
| Language | Java |
| GUI Toolkit | Java Swing, AWT |
| Event Handling | ActionListener / Swing events |
| IDE | NetBeans / Eclipse / IntelliJ IDEA |
| Version Control | Git & GitHub |

---

## 📂 Project Structure
```
Hotel_Management_System/
├── HotelManagemet/
│   └── HotelManagementmain/
│       └── src/
│           └── cse215/        # Java source files (package: cse215)
└── README.md
```

---

## ✅ Prerequisites
- **Java JDK 8 or higher**: [Download](https://www.oracle.com/java/technologies/downloads/)
- A Java IDE (NetBeans, Eclipse, or IntelliJ IDEA)
- Git (optional, for cloning)

Check your Java installation:
```bash
java -version
javac -version
```

---

## Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/Abu-yousuf-Neshad/Hotel_Management_System.git
   ```
2. **Navigate to the project**
   ```bash
   cd Hotel_Management_System/HotelManagemet/HotelManagementmain
   ```
3. **Open in your IDE**: import/open the `HotelManagementmain` folder as a Java project.

---

## How to Run

### Option 1: Using an IDE (recommended)
1. Open the project in NetBeans / Eclipse / IntelliJ.
2. Go to `src/cse215`.
3. Find the class containing the `main` method (login or home screen class).
4. Right-click it → **Run File**.

### Option 2: Using the command line
```bash
cd src
javac cse215/*.java
java cse215.<MainClassName>
```
Replace `<MainClassName>` with the class that contains `public static void main(String[] args)`.

---

## How to Use
1. Launch the application.
2. Log in with your credentials.
3. From the main window, choose an operation:
   - **Rooms**: add or manage room details
   - **Guests**: register a new guest
   - **Booking**: assign a room to a guest
   - **Check-out / Billing**: finalize stay and view the bill
4. Close the window to exit the application.

---

## 🧠 Object-Oriented Concepts Used
| Concept | Application in the Project |
|---|---|
| Classes & Objects | Rooms, guests, bookings modeled as classes |
| Encapsulation | Private fields with getters/setters |
| Inheritance | Shared behavior across related classes |
| Polymorphism | Method overriding / overloading |
| Collections | `ArrayList` for storing records |
| Exception Handling | Input validation and error messages |
| Event Handling | Button and form actions in Swing |

---

## 🔮 Future Improvements
- Database integration (MySQL / SQLite) for permanent storage
- Role-based access (admin vs. receptionist)
- Export bills and reports as PDF
- Room availability calendar
- Improved UI theme and responsiveness
- Input validation and data encryption for passwords

---

## 🤝 Contributing
Contributions and suggestions are welcome.
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## Author
**Abu Yousuf Neshad**
GitHub: [@Abu-yousuf-Neshad](https://github.com/Abu-yousuf-Neshad)

---

## 📄 License
This project was created for educational purposes. Add a `LICENSE` file (e.g., MIT) if you want to allow reuse.
