# OS Algo Visualizer

An interactive, browser-based visual simulator for CPU scheduling algorithms — designed to help learners and educators understand how processes are scheduled in modern operating systems. Built as part of an academic project under the team name **Thread Squad**, this tool brings theoretical scheduling concepts to life with real-time Gantt charts and metric analysis.

---

## 🌟 Key Features

- 🔄 Simulates 5 Major CPU Scheduling Algorithms:
  - First-Come-First-Serve (FCFS)
  - Priority Scheduling
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Multilevel Queue (MLQ)

- 📊 Dynamic Gantt Chart Visualization
- 📈 Real-time calculation of:
  - Waiting Time
  - Turnaround Time
  - Completion Time
  - Response Time

- ✅ MathJax integration for displaying calculation formulas
- 📱 Fully responsive UI using **HTML, CSS, Bootstrap**
- 🧠 No backend required – Runs entirely in the browser with **JavaScript**

---

## 🚀 How It Works

1. **Input Fields:** Enter process details like Process ID, Arrival Time, Burst Time, Priority, etc.
2. **Choose Algorithm:** Select any of the five scheduling algorithms.
3. **Visualize:** Get instant Gantt charts and performance metrics based on your input.
4. **Learn:** Understand how different algorithms behave and affect process scheduling.

---

## 🧩 System Design

- **Frontend:** HTML5, CSS3 (Bootstrap), JavaScript (Vanilla)
- **Code Modules:**
  - `cpu-scheduler.js`: Core logic for all algorithms
  - `index.html`: Interface for user input and output display
  - `styles.css`: Styling and layout structure

- **No Dependencies or Frameworks Required**
- **Deployment Ready:** Can be hosted as a static site on GitHub Pages, Netlify, or similar platforms

---

## ✅ Project Scope & Milestones

| Phase   |            Feature            |   Status  |       Contributors          |
|---------|-------------------------------|-----------|-----------------------------| 
| Phase 1 | FCFS Algorithm – UI & Logic | ✅ Complete | Tiya Rajput, Gunjan Raghav |
| Phase 2 | Priority Scheduling | ✅ Complete | Taru Kulshrestha |
| Phase 3 | MathJax & Output Enhancements | ✅ Complete | Sakshi Negi |
| Phase 4 | SJF Scheduling | ✅ Complete | Tiya Rajput |
| Phase 5 | Round Robin | ✅ Complete | Gunjan Raghav |
| Phase 6 | Multilevel Queue | ✅ Complete | Taru Kulshrestha, Sakshi Negi |

---

## 🧪 Testing & Validation

| Test Area | Status | Notes |
|-----------|--------|-------|
| FCFS Logic | ✅ Pass | Verified with sample inputs |
| Priority Scheduling | ✅ Pass | Tie-breaking handled using arrival time |
| SJF Logic | ✅ Pass | Non-preemptive variant implemented |
| Round Robin | ✅ Pass | Validated across multiple quantum values |
| MLQ Scheduling | ✅ Pass | Proper queue-based separation and policies |
| Input Validation | ✅ Pass | Covers negative, missing, or invalid entries |
| Gantt Chart Rendering | ✅ Pass | Dynamically scales with burst times |
| UI Responsiveness | ✅ Pass | Tested on multiple screen sizes |
| MathJax Integration | ✅ Pass | Equations render based on selected algorithm |

---


## 👨‍💻 Developed By — *Thread Squad*

A team of Computer Science undergraduates from Graphic Era Hill University:

- **Taru Kulshrestha**
- **Tiya Rajput**
- **Gunjan Raghav**
- **Sakshi Negi**

---

## 🎓 Academic Use

This project was developed as part of the OS Lab curriculum. It aims to bridge the gap between theory and practice by giving learners a visual and hands-on way to grasp complex CPU scheduling algorithms.

---

## 🪪 License

© 2025 Thread Squad — All rights reserved.  
This project is intended for educational purposes.

