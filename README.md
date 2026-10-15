# C++ Bank Management System (Bank Extension)

A robust, console-based banking and client management application built in C++ featuring persistent flat-file storage, transaction processing, and a multi-tier menu interface.

## 🚀 Key Features
* **Complete Client Management:** 
  * View a full, formatted list of all registered clients.
  * Add new clients with automated duplicate account number validation.
  * Search for specific clients using their account number.
  * Update client details (PinCode, Name, Phone, and Account Balance).
  * Safely delete client records with confirmation prompts.
* **Transaction Processing:**
  * **Deposit:** Add funds securely to any existing account with confirmation checks.
  * **Withdraw:** Withdraw funds with real-time balance validation to prevent overdrafts.
  * **Total Balances:** Generate financial reports displaying individual balances alongside the total combined bank assets.
* **Persistent File Storage:** Automatically syncs and saves all additions, modifications, and deletions to a local flat-file database (`Clients.txt`) using custom delimiter formatting (`#//#`).
* **Interactive UI & Navigation:** Clean menu systems with screen refreshing, color formatting, and user-friendly navigation prompts.

## 🛠️ Tech Stack & Concepts Applied
* **Language:** C++
* **Data Structures & Types:** Custom `struct` (`sClient`), `vector` containers, and `enum` types (`enMainMenueOptions`, `enTransactionMenueOptions`).
* **Core Programming Concepts:**
  * File I/O stream operations (`std::fstream`, `ios::in`, `ios::out`, `ios::app`) for persistent data management.
  * String manipulation algorithms (`SplitString`, record serialization/deserialization).
  * Stream formatting and manipulators (`std::setw`, `std::left`).
  * Modular procedural architecture separating business logic, file handling, and UI screens.

## 💻 How to Run
1. Open your C++ development environment (such as **Visual Studio** or any standard IDE).
2. Create a new C++ project and paste the source code into your `main.cpp` file.
3. Ensure a text file named **`Clients.txt`** is placed in your project directory (or let the program create/append data via file streams).
4. Build and run the executable to launch the interactive Main Menu.
