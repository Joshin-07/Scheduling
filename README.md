#  Memory Management Simulator — First Fit

An interactive web-based simulator to visualize the **First Fit memory allocation algorithm** used in Operating Systems. This project demonstrates how memory is allocated using **Fixed Partitioning** and **Variable Partitioning** with real-time visualization.

---

## 🛠️ Built With

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="45" alt="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="45" alt="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="45" alt="JavaScript"/>
</p>

---

## 🚀 Features

- First Fit memory allocation algorithm
- Supports:
  - Fixed Partitioning
  - Variable Partitioning (dynamic splitting)
- Real-time memory visualization
- Displays:
  - Allocated memory
  - Free memory
  - Internal fragmentation
  - External fragmentation
- Dynamic block management (add/remove blocks)
- Interactive and modern UI

---

## 🧩 How It Works

### 1. Setup Memory Blocks
- Enter block sizes (default: `100, 500, 200, 300 KB`)
- Add or remove blocks as needed

---

### 2. Select Partitioning Type

#### 🔹 Fixed Partitioning
- Blocks have fixed sizes  
- May cause **internal fragmentation**

#### 🔹 Variable Partitioning
- Blocks split dynamically  
- Eliminates internal fragmentation  
- May cause **external fragmentation**

---

### 3. Allocate a Process
- Enter:
  - **Process ID** (e.g., `P1`)
  - **Process Size (KB)**
- Click **Allocate Memory**
---

## ⚙️ Installation & Setup

### 1. Clone the Repository
git clone https://github.com/Joshin-07/memory-management-simulator.git

### 2. Navigate to Project Folder
cd memory-management-simulator

### 3. Run the Application
Open index.html in your browser
OR
Use Live Server (recommended in VS Code)

---
## 🎯 Learning Objectives

This project helps you understand:
- Memory management in Operating Systems
- First Fit allocation algorithm
- Difference between Fixed and Variable Partitioning
- Internal vs External Fragmentation
- How processes are allocated in memory
- Visualization of memory allocation techniques
  
---
## Deployment


---
## License 
This project is licensed under the MIT License.
