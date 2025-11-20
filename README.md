# 📊 Seqkit Paired-End Metrics Calculator

A simple, standalone **HTML tool** that instantly converts `seqkit stats -a` output into final paired-end metrics—no internet connection, installation, or external dependencies required.

Just open the file in your browser, paste your stats, and get a clean, standardized, report-ready results table.

---

## 🚀 Key Features

### 🔁 Instant Paired-End Conversion
Automatically multiplies:
- **num_seqs (Reads)** × 2  
- **sum_len (Bases)** × 2  

to generate accurate paired-end totals.

### 📈 QC Metrics Included
Directly reads and displays:
- **Q20 (%)**
- **Q30 (%)**
- **GC (%)**

### 📐 Standardized Output
All values (GB, MR, MB) are formatted to **two decimal places** for consistent reporting.

### 🔒 100% Local & Secure
Runs entirely in your browser.  
No data is uploaded, stored, or transmitted.

---

## 🧩 How to Use the Calculator

### 1. Download the HTML file
Save **`SEQ-STAT_calculator.html`** to your desktop or a shared project folder.

### 2. Open in any browser
Double-click the file to launch it in Chrome, Edge, Firefox, or any modern browser.

### 3. Paste your data
Copy the complete output of:

```bash
seqkit stats -a *R1*
