# ⌨️ Typing Speed Test – C++ Console Application

A Windows-based interactive **Typing Speed Test** built using C++. This project allows users to measure and improve their typing speed and accuracy across multiple difficulty levels. The application runs entirely in the terminal with real-time feedback and stores results in a local leaderboard.

---

## 🎯 Features

- ✅ Difficulty levels: Easy, Medium, Hard, Expert
- 🔤 Color-coded character highlighting (correct, incorrect, current)
- ⏱️ Live progress bar and timer
- 📝 Real-time performance analysis:
  - Words Per Minute (WPM)
  - Accuracy percentage
  - Total time taken
- 📊 Leaderboard that stores name, WPM, accuracy, difficulty, and date
- 📈 Statistics page to view overall progress
- 💾 Local storage of scores using binary file handling

---

## 🧰 Technologies Used

- **C++** (Standard Library)
- `conio.h` – For capturing keyboard input without enter
- `windows.h` – For colored console output and delays
- `chrono` – For measuring typing duration
- `fstream` – For binary file operations

---

## 📦 File Structure

TypingSpeedTest/

├── main.cpp # Main source code

├── leaderboard.dat # Auto-generated binary file storing scores

├── README.md # Project documentation


---

## 🚀 Getting Started

### 🖥️ Run Locally (Windows Only)

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/TypingSpeedTest.git
cd TypingSpeedTest
```
2. **Compile and Run:**

Using g++:
```bash
g++ main.cpp -o TypingTest
TypingTest.exe
```



