# 📊 Thought Leadership Budget & Engagement Analysis

This project analyzes survey data from 4,000+ professionals across industries to uncover how organizations define and implement thought leadership. It explores how budget size, department ownership, and employee engagement vary by company size and sector — and includes visuals built in R to highlight key trends.

---

## 📁 Files Included

- `ThoughtLeadership.Rmd` – R Markdown file for full analysis and visualization
- (Optional) `data/thought_leadership_survey_mock_data.xlsx` – Mock or anonymized version of the dataset
- `visuals/` – Folder for charts if you want to export static versions

---

## 🛠 Tools Used

- `tidyverse` for data wrangling
- `ggplot2` for data visualization
- `janitor` for cleaning variable names
- `readxl` for Excel file import
- `reshape2`, `scales`, `RColorBrewer` for graph enhancements

---

## 📊 Visualization Sample

The primary graph uses **faceted bar charts** to show how budget allocations vary by company revenue bracket. The visual helps question assumptions about whether higher-revenue companies invest more in thought leadership.

---

## 🔍 Key Insights

- **Budget allocation is not linear** with revenue size — large companies often distribute across both low and high tiers.
- **Business Development and C-Suite leadership** correlate with higher internal engagement in TL.
- The **mid-range budget ($100k–500k)** appears to be a standard across industries.

---

## 🧠 How to Run

1. Open the `.Rmd` file in RStudio
2. Make sure the Excel file is placed in a folder called `data/`
3. Knit the file to HTML or run code chunks interactively

---

## ✨ Author

Jenny Jiménez – Data Journalist & Analyst  
This project was part of a broader editorial and research initiative focused on leadership and brand strategy.

---

*Note: This analysis was built using anonymized or mock data in order to respect confidentiality guidelines.*
