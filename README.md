# SIEM SOC Master Consolidation & Analytics Dashboard

A high-performance, browser-based tool designed for **Cyber Security Engineers** to merge, deduplicate, and visualize SIEM alert logs. This tool focuses on aggregating repetitive alerts while maintaining strict column integrity.

## 🚀 Key Features
* **Multi-File Support:** Upload 4+ Excel/CSV files simultaneously.
* **Intelligent Deduplication:** Groups by `Event Name` and sums the `Count` field.
* **Strict Column Focus:** Only processes `Event Name`, `Event Severity Category`, `Fine-tune Status`, `Incident Resolution`, and `Count`.
* **Unique Color Coding:** Assigns individual colors (Red, Blue, Yellow, etc.) to each unique Event Name.
* **Noise Analysis:** Automatically identifies "Top Noisy Rules" based on False Positive counts.
* **One-Click Export:** Download a consolidated `.xlsx` report without row/column overlay.

## 🛠️ Usage
1. Open `index.html` in any modern browser.
2. Drag and drop your SIEM Excel files into the upload zone.
3. View the generated Bar and Pie charts for Alert Name vs. Count.
4. Click **Export to Excel** to save the final consolidated report.

## 📊 Requirements Met
- [x] Process more than 4 sheets.
- [x] Remove duplicates by merging counts into a single Alert Name row.
- [x] No overlay of data in columns or rows.
- [x] Dynamic Chart/Graph generation.
