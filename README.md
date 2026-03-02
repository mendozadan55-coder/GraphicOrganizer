# 📊 Compact Data Tracker

A lightweight, browser-based data tracking tool for comparing **Theoretical (Reference)** and **Measured (Actual)** datasets.

Built using vanilla HTML/CSS/JavaScript and powered by Chart.js.

---

## 🔎 Overview

Compact Data Tracker allows users to:

- Input theoretical (expected) data
- Input measured (actual) data
- Automatically calculate **percent error**
- Compute **mean percent error**
- Visualize datasets using scatter plots
- Save and load historical sessions locally

Designed for:

- Engineering laboratory experiments  
- Physics data comparison  
- Electronics testing  
- Academic research data tracking  

---

## 🚀 Features

### ✅ Dual Scatter Graphs
- Separate charts for theoretical and measured data
- Data automatically sorted by X value

### ✅ Automatic % Error Calculation

**Formula used:**

% Error = ((Measured Y − Theoretical Y) / Theoretical Y) × 100

- Matches data using identical X values
- Displays % error per entry
- Computes Mean % Error

### ✅ Local Session History
- Save dataset snapshots
- Load previous sessions
- Delete saved entries
- Uses browser localStorage (no internet required)

### ✅ Mobile-Friendly Interface
- Compact layout
- Dark theme
- Touch-friendly controls

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Chart.js (via CDN)  

---

## 📂 Project Structure
