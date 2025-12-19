# 🍅 Pomodoro Productivity App (Python + Tkinter)

A **desktop Pomodoro timer application** built with **Python and Tkinter**, enhanced with a **custom UI, session tracking database, and productivity streaks** to help users build consistent focus habits.

This project goes beyond a basic timer by combining **UI design**, **state management**, and **persistent data storage** in a clean, interview-ready architecture.

---

## ✨ Features

### ⏱ Core Pomodoro Functionality
- Work sessions, short breaks, and long breaks
- Start, stop, and reset controls
- Real-time countdown display
- Audible alert and completion popup when a session ends

### 🎨 Custom UI & UX
- Personalized wallpaper background
- Dark-themed, minimal interface
- Clean button layout with hover interactions
- Large, readable timer display

### 📊 Productivity Tracking (SQLite)
- All completed sessions are stored in a local SQLite database
- Tracks:
  - Session type (work / break)
  - Duration
  - Completion timestamp

### 🔥 Streak System
- Automatically calculates **daily productivity streaks**
- Displays the current streak directly on the main screen
- Encourages consistency and habit formation

### 📜 History View
- View past sessions in a structured layout
- Sorted by most recent sessions
- Foundation for future analytics (graphs, weekly stats, heatmaps)

---

## 🛠 Tech Stack

- **Python 3**
- **Tkinter** – GUI
- **SQLite3** – persistent storage
- **Pillow (PIL)** – image handling
- **Git & GitHub** – version control

---

## 📂 Project Structure

```text
pomodoro/
│
├── assets/
│   └── wallpaper.jpg        # Custom background image
│
├── pomo.py                  # Main application logic
├── sessions.db              # SQLite database (auto-created)
├── README.md
├── .gitignore


How It Works (High-Level Design)
UI Layer (Tkinter)
Handles buttons, labels, layout, and user interactions.
Timer Engine
Uses root.after() for non-blocking countdown updates.
Persistence Layer (SQLite)
Every completed session is stored locally for analytics and streak calculation.
Streak Logic
Computes consecutive-day work sessions using timestamps from the database.
This separation makes the code easy to debug, extend, and explain in interviews.

📌 Why This Project Stands Out
✔ Not just a tutorial app
✔ Combines UI + database + logic
✔ Demonstrates real-world state handling
✔ Shows understanding of persistence and user experience
✔ Easily extensible (graphs, themes, cloud sync)

🔮 Future Improvements
Productivity graphs (weekly/monthly)
Light/Dark theme toggle
Export history as CSV
Notifications
Cloud sync for multi-device usage

👩‍💻 Author
Hema Kunchala
Computer Science Student | Aspiring ML & Software Engineer
GitHub: https://github.com/hemakunchala05-hub


