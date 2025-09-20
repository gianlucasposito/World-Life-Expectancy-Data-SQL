# World Life Expectancy Analysis (SQL Project)

 This project analyzes global **life expectancy** trends from 2000 to 2015, using health, social, and economic indicators across 193 countries, including:

- 🧪 Immunization-related factors (HIV/AIDS, Polio, Diphtheria)  
- ⚰️ Mortality factors  
- 💰 Economic factors  
- 👥 Social factors  

---

## 📂 File Information

- `README.md` # Documentation
- `WorldLifeExpectancy.csv` # Dataset
- `World_Life_Expectancy_SQL.ipynb` # Jupyter notebook with SQL analysis

---

## 🗂️ 📊 About the Dataset

- Source: **World Health Organization (WHO)** and **United Nations**  
- Size: **2941 rows × 18 columns**
- Target variable: **Life expectancy** 

| Column | Description |
|--------|-------------|
| `Row_ID` | Unique identifier for each record |
| `Country` | Country name |
| `Year` | Year of observation |
| `Status` | Country status: *Developed* or *Developing* |
| `Life expectancy` | Average life expectancy in years (target variable) |
| `Adult Mortality` | Adult death rate (per 1000 population) |
| `infant deaths` | Infant deaths (per 1000 population) |
| `under-five deaths` | Deaths of children under age 5 (per 1000 population) |
| `percentage expenditure` | Health expenditure as % of GDP |
| `Measles` | Reported measles cases (per 1000 population) |
| `Polio` | Immunization coverage for Polio (percentage) |
| `Diphtheria` | Immunization coverage for Diphtheria (percentage) |
| `HIV/AIDS` | Deaths due to HIV/AIDS (per 1000 population) |
| `BMI` | Average Body Mass Index of the population |
| `thinness 1-19 years` | Prevalence of thinness (age 10–19, %) |
| `thinness 5-9 years` | Prevalence of thinness (age 5–9, %) |
| `Schooling` | Average years of schooling |
| `GDP` | Gross Domestic Product per capita (in USD) |

---

## 📂 Project Overview

The project  is divided into three main stages:

1. **Database Creation (SQLite)**

2. **Data Cleaning**
   - Standardized column names.
   - Handled missing and null values.
   - Removed duplicate records.
   - Check any potential anomalies in the column values.

3. **Data Analysis**
   - Conducted exploratory queries in SQL.
   - Examined life expectancy trends across countries.
   - Analyzed relationships between life expectancy and:
     - GDP  
     - Scholarity  
     - Status (Developed vs Developing countries)  
     - Adult mortality  

📊 Key Insights

- 🌱 **Life expectancy increases with GDP**, showing strong positive correlations.  
- 🌍 **Developed countries consistently report higher life expectancy** compared to developing nations.  
- 💀 **Adult mortality is inversely correlated** with life expectancy, highlighting the importance of healthcare access.  
- 📈 Global trend shows **steady improvement in life expectancy over the past decades**.  

---

## 🚀 How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/gianlucasposito/World-Life-Expectancy-Data-SQL.git
   cd World-Life-Expectancy-Data-SQL
