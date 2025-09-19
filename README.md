# World Life Expectancy Analysis (SQL Project)

## 📊 About the Dataset

### Context
This project explores global **life expectancy** using health, social, and economic indicators. Unlike past studies that relied on limited variables or single-year data, this dataset spans **2000–2015** and covers **193 countries**, including:  

- 🧪 Immunization-related factors (HIV/AIDS, Polio, Diphtheria)  
- ⚰️ Mortality factors  
- 💰 Economic factors  
- 👥 Social factors  

---

## 📂 Data Information

- **WorldLifeExpectancy.csv** – Main dataset used for analysis  
  - Rows: **2938**  
  - Columns: **22**  
  - Target: `Life expectancy`

## 🗂️ Data Dictionary

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

## 🛠️ Project Structure

- `data/` – Dataset files  
- `sql/` – SQL queries for analysis  
- `notebooks/` – (Optional) Jupyter or R scripts for preprocessing  
- `README.md` – Project documentation  

---

## 🚀 How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
