# 🐍 Python for Everybody (University of Michigan - Coursera)

This repository showcases my completed exercises and projects from the **Python for Everybody Specialization** by the **University of Michigan** on Coursera.  
It demonstrates my journey in mastering Python fundamentals, data handling, web scraping, and database management — all skills that have strengthened my work as a **Cybersecurity Analyst**.

> 🧠 My favorite part of the course was using **BeautifulSoup** and **Python** to extract and analyze web data — a skill highly relevant to data gathering and security research.

---

## 📘 Course Modules Overview

### 1. **Python for Data Structures**
Focuses on the core elements of Python programming:
- Control structures, loops, conditionals
- Working with strings, lists, tuples, and dictionaries  
- Includes real-world text datasets like `romeo.txt`, `mbox-short.txt`, and `words.txt`

📂 **Folder:** `Python for Data structure/`

---

### 2. **Using Python to Access Web Data**
Explores how Python interacts with the web and APIs:
- Working with **HTTP**, **sockets**, and **requests**
- Parsing and processing **HTML**, **XML**, and **JSON**
- Exercises such as `ex_11.4.py`, `ex_13.10.py`, and `ex_11.4try.py.py`
- Contains output logs and screenshots of successful runs

📂 **Folder:** `using python to access web data/`

---

### 3. **BeautifulSoup (Web Scraping)**
Dedicated to practical web scraping with **BeautifulSoup** (`bs4`):
- Exercises include `ex_12.4.py`, `ex_12.5.py`, and `ex_13.7.py`
- Demonstrates HTML parsing and data extraction techniques
- Includes example results and screenshots (`ex.12.4.png`, etc.)

📂 **Folder:** `Beautifulsoup/`

---

### 4. **Databases and Applications**
Covers data persistence and database-driven applications:
- Projects built using **SQLite3**
- Files like `emaildb.py`, `tracks.py`, and `.db` databases
- Key submodules:
  - `opengeo/` → Geocoding and geographic data processing  
  - `pagerank/` → Web spidering and PageRank visualization  
  - `ex15.11/` → JSON-based roster database  
  - `tracks/` → Music track database demo

📂 **Folder:** `py4e/`

---

### 5. **Screenshots**
A collection of screenshots showing successful code execution and project results.

📂 **Folder:** `Screenshot/`

---

## 🗂 Repository Structure

```
python_for_everyone_extracted/
│
├── Beautifulsoup/                      # Web scraping exercises with BeautifulSoup
│   ├── Beautiful_soup.py
│   ├── ex_12.4.py, ex_12.5.py, ex_13.7.py (and text results)
│   ├── screenshots (e.g., ex.12.4.png)
│   └── bs4 library copy and soupsieve utilities
│
├── py4e/                               # Main “Python for Everybody” course files
│   ├── emaildb.py, tracks.py, awesome.py, ex*.py
│   ├── Databases: .db, .sqlite, .sqbpro
│   ├── Submodules:
│   │   ├── opengeo/      → Geodata and geocoding exercises
│   │   ├── pagerank/     → Web spidering & PageRank visualization
│   │   └── ex15.11/      → Roster / JSON database exercises
│   ├── README.txt
│   └── tracks/           → Music track database example
│
├── Python for Data structure/          # Exercises on lists, dictionaries, strings, and loops
│   ├── ex_6.5.py, ex_7.1.py, ex_8.4.py, ex_9.4.py …
│   ├── romeo.txt, mbox-short.txt, words.txt (sample data)
│
├── Screenshot/                         # Screenshots of exercise results
│   ├── Screenshot (15).png … Screenshot 2025-10-09 211824.png
│
└── using python to access web data/    # Networking, sockets, and APIs
    ├── ex_11.4.py, ex_13.10.py (and PNG/TXT results)
    ├── ex_11.4try.py.py (HTTP handling practice)
```
---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/python-for-everyone.git
   cd python-for-everyone

2. **Create a virtual environment**

   ```bash
   python -m venv env
   source env/bin/activate     # macOS/Linux
   env\Scripts\activate        # Windows

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt

   **(If `requirements.txt` is missing, install manually:)**

   ```bash
   pip install beautifulsoup4 requests sqlite3

---

## 🚀 How to Run Examples

**Run a data structure exercise:**

cd "Python for Data structure"
python ex_9.4.py

**Run a web data access script:**

cd "using python to access web data"
python ex_11.4.py


**Run a BeautifulSoup example:**

cd Beautifulsoup
python ex_12.5.py

**Run a database project:**

cd py4e
python tracks.py

---

## 🧠 Key Learning Outcomes

* Python scripting and control structures
* File handling and data manipulation
* Web scraping using **BeautifulSoup**
* Accessing REST APIs and parsing **JSON/XML**
* Working with **SQLite** databases
* Visualizing relationships (PageRank project)
* Applying Python for cybersecurity data automation

---

## 📸 Screenshots

Screenshots showing the output and progress of each project are available in the `/Screenshot/` folder.

---

## 📄 License

This repository is shared for **educational and portfolio purposes only**.
All scripts and notes authored by **Isaac Oppong** are released under the **MIT License**.

---

## 👤 Author

**Isaac Oppong**
📧 [i.oppong999@gmail.com](mailto:i.oppong999@gmail.com)
🌐 [https://www.linkedin.com/in/oppong-isaac-ks999](https://github.com/ksmile999)
🎓 Course: [Python for Everybody – University of Michigan](https://www.coursera.org/specializations/python)

---

> ⭐ *If this helped you or inspired your learning, give the repo a star and share it with others!*


---
