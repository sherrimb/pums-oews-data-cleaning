# pums-oews-data-cleaning
# 🧹 Merging & Cleaning PUMS + OEWS Occupational Data

This project demonstrates how to clean and merge two real-world datasets:  
**PUMS (Public Use Microdata Sample)** and **OEWS (Occupational Employment and Wage Statistics)**.  
We focus on California workers to explore occupational codes, job titles, and hourly wages.

---

## 📊 Datasets Used

- `cleaned_pums_2021.csv`: Contains demographic and employment info from the U.S. Census Bureau
- `oes_research_2021_sec_55-56.xlsx`: Contains wage and occupation data from the U.S. Bureau of Labor Statistics

---

## ⚙️ What This Project Does

- Loads, cleans, and filters both datasets
- Creates a new `OCC_CODE` column by copying and formatting `SOCP`
- Filters for California-only data from OEWS
- Merges the datasets on `OCC_CODE`
- Drops unused or duplicate columns (`SOCP`, `AREA_TITLE`)
- Saves the cleaned, merged dataset as `cleaned_merged_pums_oews.csv`

---

## 🧠 Skills Demonstrated

- Data wrangling and preprocessing with **Pandas**
- String cleaning and feature creation
- Merging multiple datasets on a key field
- Dropping NA values and resetting index
- Exporting to CSV

---

## 🔧 Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 🚀 Next Steps (Optional Ideas)

- Visualize wage distributions by gender and occupation
- Create bar charts of top-paying jobs in California
- Add interactive dashboards with Plotly or Tableau
- Compare occupational trends across other U.S. states

---

## 🗃️ File Structure
├── cleaned_pums_2021.csv
├── oes_research_2021_sec_55-56.xlsx
├── cleaned_merged_pums_oews.csv  ← Final output
├── pums_oews_merge.ipynb         ← Jupyter Notebook
└── README.md

---

## 💬 Let’s Connect

Made with 💻 by Sherri Killough 
Feel free to connect with me on [LinkedIn](https://linkedin.com/in/sherrikillough) or view more projects on [GitHub](https://github.com/sherrimb).
