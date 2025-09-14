# IBM Data Analyst Capstone

## 📛 Badges
<!-- badges: start -->
![IBM Data Analyst](https://img.shields.io/badge/IBM%20Data%20Analyst-Certified-blue.svg)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/CodeStarter25/IBMDataAnalystCapstone)
[![IBM Data Analyst Certificate](https://img.shields.io/badge/Certificate-IBM%20DA-blue)](https://coursera.org/share/99809bb766f6702aa7a0d11362b8c1cb)
![GitHub stars](https://img.shields.io/github/stars/CodeStarter25/IBMDataAnalystCapstone?style=social)

<!-- badges: end -->



This repository contains the complete work and labs from my **Capstone Project** for the IBM Data Analyst Professional Certificate. It showcases the **skills, techniques, and tools** I’ve developed to **manipulate, clean, and visualize data** throughout the course.

---

## 📌 Project Overview


### 🔹 Introduction

As part of this capstone, I assumed the role of a Data Analyst at a global IT and business consulting firm. The company is focused on staying competitive in the rapidly evolving tech landscape by regularly analyzing data to forecast **emerging and in-demand skills**.


### 🔹 Role & Responsibilities

My primary objective was to collect, analyze, and visualize data from diverse sources to support this year’s internal report on in-demand developer skills. Key data sources included:

* Job postings
* Training portals
* Developer surveys (e.g., **Stack Overflow Developer Survey 2024**)

Once collected, I processed the data using **data wrangling**, conducted **exploratory data analysis**, and visualized the results using **Google Looker Studio**. The final deliverables include a presentation highlighting the trends and a dashboard built using BI tools.

---

## 🛠️ Skills & Tools Applied

* **Web Scraping** with `BeautifulSoup`
* **REST API** integration
* **Python Libraries**: `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`
* **Data Cleaning** and **Wrangling**
* **Exploratory Data Analysis (EDA)**
* **Data Visualization** using:
  * Google Looker Studio
  * Matplotlib & Seaborn (custom plots)
* **Country Standardization** using `pycountry` (Alpha-3 country codes)

---

## 📊 Key Themes Explored

* Most in-demand programming languages
* Popular and emerging database technologies
* Frequently used platforms and web frameworks
* Developer demographics and satisfaction levels
* Global salary and location-based discrepancies

---

## ✨ Highlights to Explore

To quickly see the core of my skills and approach, I recommend checking out:

[Lab 21](https://github.com/CodeStarter25/IBMDataAnalystCapstone/blob/main/Lab_21_Pie_Charts.ipynb): Features a custom function I developed to dynamically create all pie charts from Task 2, showcasing my ability to write reusable, efficient code.

[Presentation PDF](https://github.com/CodeStarter25/IBMDataAnalystCapstone/blob/main/IBM_DA_Capstone_Presentation.pdf): Detailed insights and visual storytelling demonstrating my data interpretation and communication skills.

[Dashboard PDF](https://github.com/CodeStarter25/IBMDataAnalystCapstone/blob/main/IBM_Capstone_DashBoard.pdf): Interactive reports built with Google Looker Studio, highlighting my proficiency in data visualization tools.

The final labs: These labs showcase the best visualizations using the available data, including unified naming conventions and simple Python techniques that highlight key insights effectively. 

These files best illustrate how I apply technical expertise and creativity to real-world data challenges.

---
## 💬 Notes

This repository can serve as a learning resource or reference for others pursuing the IBM DA Certificate or similar data projects. I included additional steps and improvements in later stages, especially in the final labs, to better understand and present the data.

🚫 Please do not misuse this repository.
This project reflects my personal efforts and progress through the IBM Data Analyst Professional Certificate.
While it's shared under the MIT License for educational use, submitting this work as your own in academic or graded settings (e.g., Coursera or IBM courses) violates the Honor Code and constitutes plagiarism.

I welcome learners and professionals who want to learn from or build on this — but please, do your own work.
You learn through struggle, not imitation.

---

## 🖥️ Running Locally (Optional)

> 🔹 *Note: If you're just browsing, all `.ipynb` notebooks can be viewed directly on GitHub — no need to download anything. Click on any file and it will open automatically in your browser.*

If you want to **run the code locally on your machine**, follow these steps:

### 1️⃣ Install Visual Studio Code (VS Code)

* Download and install it from [https://code.visualstudio.com](https://code.visualstudio.com)
* Make sure to install the **Python** and **Jupyter** extensions from the Extensions panel inside VS Code.

### 2️⃣ Clone This Repository

Open a terminal or Git Bash and run:

```bash
git clone https://github.com/CodeStarter25/IBMDataAnalystCapstone.git
cd IBMDataAnalystCapstone
```

### 3️⃣ (Optional) Set Up a Virtual Environment

While not strictly required, a virtual environment is recommended for keeping dependencies clean.

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# OR
source venv/bin/activate  # For macOS/Linux
```


### 4️⃣ Install Required Python Libraries

Most of the labs require only `pandas`, `numpy`, and `seaborn`, but if you want to run all labs seamlessly, I recommend installing the following libraries using `pip`:

```bash
pip install pandas numpy seaborn matplotlib requests pillow flask pycountry openpyxl
```

> 🔸 `BeautifulSoup` is part of `bs4`, which is often pre-installed in environments like Jupyter, but can be manually installed if needed:

```bash
pip install beautifulsoup4
```

### 🔚 Notes:

* To exit your virtual environment when done, simply run:

```bash
deactivate
```

### 5️⃣ Open in VS Code and Start Exploring

* Launch VS Code and open the cloned folder.
* Open any `.ipynb` file — the Jupyter extension will render it like a notebook.
* Run cells interactively or explore the code statically.


> 🔸 If you encounter any issues, make sure your Python and pip versions are up to date.

---

## ⚠️ Disclaimer

These are **my personal solutions and approaches** for the IBM Data Analyst Professional Certificate.
They are provided **for educational purposes and reference only**.
