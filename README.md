# System Monitor Tool (C++)
![Description](image/image.png)


## 🧠 Overview
A real-time system monitoring tool built in C++ for Linux. Displays CPU usage, memory stats, and running process details, similar to the `top` command.

## ⚙️ Features
- Lists active processes with PID, name, memory & CPU usage
- Real-time updates every 2 seconds
- Built using Linux `/proc` filesystem
- Developed and tested in WSL (Ubuntu on Windows)

## 🛠️ Tech Stack
- C++17
- Linux `/proc` interface
- Multithreading (for refresh loop)

## ▶️ Run
```bash
make
./build/system_monitor

