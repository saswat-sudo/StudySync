#  StudySync

**StudySync** is a simple academic study portal developed using **HTML and CSS**. It provides a centralized interface for accessing subject information, lecture notes, and class timetables.

The project is designed as a student-focused web resource for organizing and accessing academic materials in one place.

##  Features

*  Centralized academic dashboard
*  B.Tech Computer Science Engineering study portal
*  Subject-wise navigation
*  Lecture notes for individual subjects
*  Subject-wise class timetables
*  Frame-based webpage layout
*  Custom HTML and CSS styling
*  Internal navigation between pages
*  University and course information

##  Subjects

The portal currently contains the following subjects:

1. **Advanced Web Programming**
2. **Industrial IoT and Automation**
3. **Mathematical Problem Solving**
4. **Operating System Concepts**

Each subject has its own page with links to lecture notes and timetable information.

##  Project Structure

```text
StudySync/
│
├── index.html
├── file1.html
├── file2.html
├── file3.html
├── file4.html
│
├── awp.html
├── awplec.html
├── awptimetable.html
│
├── IIOT.html
├── IIOTlec.html
├── IIOTtimetable.html
│
├── MPS.html
├── MPSlec.html
├── MPStimetable.html
│
├── OS.html
├── OSlec.html
├── OStimetable.html
│
└── StudySync.code-workspace
```

##  How It Works

The main `index.html` file creates the overall page layout using HTML frames. It loads:

* `file1.html` → Header section
* `file2.html` → Subject navigation
* `file3.html` → Subject selection area
* `file4.html` → Assignment/student information area

The navigation page provides links to the four subjects, which load their respective information into the designated frame.

For example, the subject navigation contains links to Advanced Web Programming, Industrial IoT and Automation, Mathematical Problem Solving, and Operating System Concepts.

##  Academic Content

### Advanced Web Programming

The AWP section contains lecture material covering topics such as:

* Web architecture
* HTTP
* HTML and HTML5
* CSS
* JavaScript
* jQuery
* AJAX
* JSON
* Responsive Web Design
* Bootstrap
* PHP
* Drupal
* XML
* Web Security

The course material also includes topics such as SQL Injection, XSS, and OWASP security standards.

### Industrial IoT and Automation

The IIoT section covers:

* IIoT architecture
* IoT and IIoT concepts
* Sensors and actuators
* Raspberry Pi
* NodeMCU
* Arduino
* MQTT
* LoRa
* ZigBee
* Bluetooth/BLE
* OPC UA
* Cloud, Fog and Edge computing
* PLC
* SCADA
* Automation
* IIoT security

The material also lists practical/project areas such as smart energy meters, smart agriculture, Bluetooth-based automation, temperature-controlled systems, and smart baggage tracking.

### Mathematical Problem Solving

The MPS section covers:

* Algorithms and data structures
* Algorithm efficiency
* Sorting and searching
* Brute-force algorithms
* DFS and BFS
* Divide and conquer
* Merge Sort
* Quick Sort
* Dynamic programming
* Floyd's algorithm
* Knapsack problem
* Greedy algorithms
* Prim's algorithm
* Kruskal's algorithm
* Dijkstra's algorithm
* Huffman trees
* P, NP and NP-Complete problems

These topics are organized across seven modules in the provided course material.

### Operating System Concepts

The OS section covers:

* Operating system fundamentals
* OS structures and services
* System calls
* Process management
* Process scheduling
* Threads
* Inter-process communication
* Synchronization
* Semaphores
* Deadlocks
* Memory management
* Paging
* Virtual memory
* Page replacement
* File systems
* Storage management
* Disk scheduling
* Linux commands and permissions

The course material includes practical work involving FCFS, SJF, Round Robin, Priority Scheduling, Banker’s Algorithm, FIFO/LRU/Optimal page replacement, Linux commands, and Linux file permissions.

##  Technologies Used

* **HTML5**
* **CSS3**
* **Visual Studio Code**
* **VS Code Live Server**

No backend or database is currently required.

##  How to Run

### Option 1 — Open Directly

Clone the repository:

```bash
git clone https://github.com/saswat-sudo/StudySync.git
```

Enter the project directory:

```bash
cd StudySync
```

Open `index.html` in a web browser.

### Option 2 — Using VS Code Live Server

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Open `index.html`.
4. Right-click the file.
5. Select **Open with Live Server**.

##  Project Purpose

The purpose of StudySync is to create a simple academic resource portal where students can access their subject information, lecture materials, and timetables through a single interface.

##  Future Improvements

Possible future improvements include:

* Responsive design for mobile devices
* Replace HTML frames with modern CSS layouts
* Add a search function
* Add student login/authentication
* Add downloadable study materials
* Add assignment tracking
* Add examination schedules
* Add announcements
* Add dark/light mode
* Add a backend database
* Add an admin panel for managing academic content

##  Author

**Saswat Kumar Pandey**

B.Tech – Computer Science Engineering
Section: G

##  License

This project is intended primarily for educational and academic purposes.
