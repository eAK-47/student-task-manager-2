# 📚 Student Task Manager — Academic Productivity Platform

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A premium, serverless, web-based productivity application engineered specifically for university students to streamline academic workflow tracking, log lecture timetables, and monitor real-time course progress indicators. Built as a core design showcase for a **User Interface Design (UID)** curriculum layout paradigm.

---

## 🎨 Core Design Language & UI/UX Principles

This application utilizes a modern **Glassmorphism Design Language** optimized for student study habits:
* **Late-Night Optimization:** Deep background palettes (`#04090d`) combined with heavy backdrop blurs (`backdrop-filter: blur(24px)`) reduce digital eye strain during late-night study blocks.
* **Ambient Depth Framework:** Fluid, multi-layered background gradient accent orbs driven by low-overhead hardware-accelerated CSS Keyframe animations give the interface an organic, floating visual depth.
* **Micro-Interactions:** Interactive buttons leverage precise client-side JavaScript Event Listeners to execute explicit mechanical translations (`translateY(-2px)`) and active radial glow structures, boosting layout *affordance signaling*.
* **Visual Information Encoding:** Core operational components are instantly identifiable through standardized color status badge states (Red for High Urgency, Gold for Pending/Medium, and Emerald Green for Completed/Low).

---

## ⚙️ Functional Architecture & State Management

The workspace operates entirely as a high-performance, serverless client-side application featuring a unified architecture workflow:

### 1. Data Capture Layer
Standard browser entry fields programmatically capture raw user values, processing strings via `.trim()` gates and format validation modules (such as Regular Expression Regex tests for academic email validation filters).

### 2. State Persistence Memory
Data persistence avoids external server delays by deploying the native **HTML5 Web Storage API (`localStorage`)**. Dynamic array collections are synchronized synchronously within distinct origin namespaces (`"studentTasks"`, `"studentSchedule"`, and `"studentProfile"`) using `JSON.stringify()` serialization strings.

### 3. Reactive Viewport Reflow (DOM Manipulation)
The presentation engine utilizes data-driven loops (`.forEach()`) to instantiate virtual memory layout nodes on the fly. Stale element sub-trees are flushed out via selective container zeroing (`.innerHTML = ""`) before running dynamic HTML template text rendering iterations. This architecture achieves an instantaneous, reactive view update without executing heavy, distracting browser page refreshes.

---

## 🛠️ Application Modules & Layout Hierarchy

The platform is mapped across a structured 6-page responsive grid architecture framework:

* **Landing Canvas (`index.html`):** Introducing the system scope, user problems, and direct product call-to-actions.
* **Workspace Dashboard (`Dashboard.html`):** The primary data control room aggregating live performance indicators, completion analytics, and module entry lanes.
* **Task Workspace (`task.html`):** Captures individual course assignments, attaches dates, sets priority status, and toggles data completion status weights in real-time.
* **Daily Timetable (`schedule.html`):** Logs structured class hours, designated campus room coordinates, and assigned faculty profiles using localized array splice arrays.
* **Notifications Board (`reminder.html`):** Visually maps color-coded alert indicators to focus user attention on imminent exam windows and project deadliness.
* **Profile Configuration (`profile.html`):** Coordinates user identity properties, academic year parameters, and study milestones across the dashboard profile fields.

---

## 🚀 How the Analytics Calculation Engine Works

The dynamic progress metric tracking uses a strict client-side data calculation equation to reflow the visual interface containers:

1. **Total Matrix Tally:** Automatically evaluates array index boundaries to isolate maximum assignment volume trackers (`tasks.length`).
2. **Filtered Predicate Search:** Sweeps elements to calculate completed subsets matching explicit boolean variables (`tasks.filter(t => t.completed).length`).
3. **Safety Zero-Gate:** Runs a conditional ternary constraint step (`total > 0 ? ... : 0`) to bypass zero division barriers, completely preventing calculation script failures like displaying `NaN%` on cards.
4. **Integer Uniformity:** Uses `Math.round()` to drop decimal trailing numbers, updating the interface text indicators and sliding gradient progress bar inline CSS style widths (`style.width`) simultaneously.

---

## 👥 Project Architects (UID Laboratory Group)

This application was engineered and designed by:
* **Vaishnav Venu** — *B.Tech Computer Science Engineering*
* **Akash S Kishor** — *B.Tech Computer Science Engineering*
* **Raj Barnawal** — *B.Tech Computer Science Engineering*
* **Praful Singh** — *B.Tech Computer Science Engineering*

*Amrita Vishwa Vidyapeetham, Department of Computer Science and Engineering*

---

## 📄 License & Academic Usage
This software layout is developed strictly as an academic coursework submission project artifact under user interface design parameters. All layout resources, structural components, and logic script systems remain free to review and scale for educational prototyping needs.
