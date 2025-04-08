# ✈️ Flight Network Booking System (C Project)

A command-line based **Flight Booking System** developed in C, which simulates a network of cities (airports) and flights between them. It allows users to register, log in, search for flights, book or cancel them, and provide feedback. The system uses graph algorithms to find optimal paths and supports both users and managers.

---

## 📌 Features

### 🧑‍💼 User Side
- Register and log in as a user.
- View all available cities (places).
- Search for flights between source and destination:
  - View all possible routes.
  - View shortest route based on cost.
- Book a flight and choose number of seats.
- View or cancel existing bookings.
- Provide reviews and ratings.

### 🛠️ Manager Side
- Register and log in as a manager.
- Add new places (cities).
- Add new flights between cities.

---

## 📊 Data Structures & Algorithms Used

- **Graph** (Adjacency List) for representing flight network.
- **Dijkstra's Algorithm** for finding the cheapest path.
- **Depth First Search (DFS)** to find all possible paths.
- **Min Heap** for efficient shortest path computation.
- **KMP (Knuth-Morris-Pratt)** algorithm for username search.

---

## 🗂️ Project Structure

| File               | Description                           |
|--------------------|---------------------------------------|
| `flightNetWork.c`  | Main source code with all logic.      |
| `users/`           | Directory storing user booking files. |

---

## 🧑‍💻 How to Compile & Run

### 🔧 Requirements
- GCC compiler
- Windows OS (uses `conio.h` and `windows.h`)

### 🔨 Compile
```bash
gcc flightNetWork.c -o flightApp
./flightApp
```
Note: If you're on Linux or macOS, remove conio.h, windows.h, and related code.
