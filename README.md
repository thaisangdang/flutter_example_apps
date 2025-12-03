# 📱 Flutter Example Apps

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

A comprehensive collection of Flutter applications demonstrating the journey from beginner UI layouts to advanced production-ready architectures. Each project focuses on specific Flutter concepts and widgets.

## 📘 Master Flutter Architecture
**Want to go beyond basics?** Check out my premium guide on building a full-scale social application.

👉 **[Master Flutter Architecture - Build a Production-Ready Social App from Scratch (100+ Page Ebook + Source Code)](https://thaisang.gumroad.com/l/flutter-architecture-build-a-social-app)**

*Learn Clean Architecture, State Management, Firebase Integration, and scalable code patterns.*

---

## 📚 Project Index

| #  | Project Name | Key Concepts | Source Code |
|----|--------------|--------------|-------------|
| 01 | **Personal Business Card** | Rows, Columns, Assets, Custom Fonts | [View Code](./link-to-repo) |
| 02 | **Counter App Extended** | `StatefulWidget`, `setState`, Basic Logic | [View Code](./link-to-repo) |
| 03 | **Dice Roller** | `Expanded` Widget, `dart:math`, Randomization | [View Code](./link-to-repo) |
| 04 | **Magic 8 Ball** | Boolean Logic, Asset Swapping, State Management | [View Code](./link-to-repo) |
| 05 | **Xylophone Instrument** | External Packages (`audioplayers`), Functions, Refactoring | [View Code](./link-to-repo) |
| 06 | **Calculator App** | `GridView.builder`, Complex Algorithms, Parsing | [View Code](./link-to-repo) |
| 07 | **BMI Calculator** | Navigation (`Navigator`), Theming, Custom Widgets | [View Code](./link-to-repo) |
| 08 | **Login & Signup UI** | Forms, Validation, `TextEditingController`, Focus Nodes | [View Code](./link-to-repo) |
| 09 | **Restaurant Menu** | `ListView.builder`, Data Models, ListTiles | [View Code](./link-to-repo) |
| 10 | **Onboarding Screens** | `PageView`, `PageController`, `smooth_page_indicator` | [View Code](./link-to-repo) |
| ...| *More coming soon* | ... | ... |

---

## 🛠 Project Details

### 1. Personal Business Card
A static UI project showcasing how to layout elements using Rows and Columns.
- **Widgets:** `CircleAvatar`, `Card`, `ListTile`, `Divider`.
- **Learning Outcome:** Understanding the Widget Tree and Asset management.

### 2. Counter App Extended
An evolution of the default Flutter app. Includes Decrement, Reset, and "Zero Floor" logic.
- **Widgets:** `FloatingActionButton`, `Row`.
- **Learning Outcome:** The basics of State management.

### 3. Dice Roller & 4. Magic 8 Ball
Interactive game apps that introduce randomness.
- **Widgets:** `Expanded`, `TextButton`.
- **Learning Outcome:** Handling user input and responsive design with Flex layouts.

### 5. Xylophone
A musical app that plays specific WAV files on tap.
- **Packages:** `audioplayers`.
- **Learning Outcome:** How to use the `pub.dev` ecosystem and refactor repeated code into functions.

### 6. Calculator
A fully functional calculator that parses math strings.
- **Packages:** `math_expressions`.
- **Learning Outcome:** Managing complex grid layouts and string manipulation.

### 7. BMI Calculator
A multi-screen application with a custom dark theme.
- **Concepts:** Passing data between screens using the Navigator.
- **Architecture:** Separation of Logic (`CalculatorBrain`) from UI (`InputPage`).

### 8. Login & Signup System
A production-standard authentication UI.
- **Concepts:** Form validation (Email regex, Password length), Password visibility toggles, and matching "Confirm Password" fields.

### 9. Restaurant Menu
A scrollable list of products using a custom Data Model.
- **Concepts:** `ListView.builder` for efficient rendering and creating Dart Classes for data structure.

### 10. Onboarding Screens
A smooth 3-page intro tutorial seen in most modern apps.
- **Concepts:** Swiping gestures using `PageView` and controlling state with `PageController`.

---