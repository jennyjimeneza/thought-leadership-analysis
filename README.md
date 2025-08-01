# 📊 Thought Leadership Budget & Engagement Analysis

This project analyzes survey data on how organizations across industries define and implement **thought leadership (TL)**. The analysis explores how budget size, departmental ownership, and employee engagement vary by company size and sector — using visuals created in R.

---

## 📁 Files Included

- `Thought_Leadership_Clean_Final.Rmd` – Cleaned and ready-to-share R Markdown file
- `data/thought_leadership_survey_mock_data.xlsx` – Anonymized mock survey dataset
- `visuals/` – Folder containing all output charts (PNG format)

---

## 🛠 Tools Used

- `tidyverse` for data wrangling
- `ggplot2` for data visualization
- `readxl` and `janitor` for data import and cleaning
- `scales`, `gridExtra`, `RColorBrewer` for styling enhancements

---

## 📊 Key Visuals

### 📌 Thought Leadership Budget by Company Revenue
![Budget Allocation by Revenue](visuals/tl_budget_vs_revenue_facet.png)
> **Insight:** Budget allocation is not linear — large companies often spread budgets across both low and high ranges.

---

### 📌 Perceived Employee Engagement by Department
![Engagement by Department](visuals/tl_engagement_by_department.png)
> **Insight:** When TL is led by the C-Suite or Business Development, employee engagement tends to be perceived as higher.

---

### 📌 Budget Ranges by Industry
![Budget by Industry](visuals/tl_budget_by_industry.png)
> **Insight:** Most industries center around a mid-range TL budget, but some (like IT and Finance) lean toward larger investments.

---

## 🔍 Summary of Insights

- **Mid-range budgets ($100k–$500k)** are common across sectors
- **Departmental leadership matters** — engagement is highest when strategic teams lead TL
- **Budget size does not scale directly** with revenue — priorities, not size, drive investment

---

## 🧠 How to Run

1. Open the `.Rmd` file in RStudio
2. Place the Excel file in a folder called `data/`
3. Knit the file to HTML or run chunks interactively

---

## ✨ Author

Jenny Jiménez – Data Journalist & Analyst  
This project was created as part of a broader editorial and insight strategy initiative.  
Mock data was used to protect confidentiality.

---

