# 📊 Week 3 – COVID-19 Data Analysis Project

## 🔍 Project Title:
**Analyzing Global COVID-19 Data Using Pandas and Matplotlib**

## 🎯 Objective:
To perform Exploratory Data Analysis (EDA) on global COVID-19 data and visualize trends in:
- Confirmed cases
- New daily cases
- Deaths
- Recovery comparisons
- Death rates by country

---

## 📂 Dataset Used:
- Source: [Our World In Data – COVID-19 Dataset](https://covid.ourworldindata.org/data/owid-covid-data.csv)
- File: `owid-covid-data.csv`

Typical columns used:
- `date`
- `location`
- `total_cases`
- `new_cases`
- `total_deaths`
- `population`
- `continent`

---

## 🛠 Tools & Libraries:
- **Google Colab**
- **Python**
- **Libraries:**
  - `pandas`
  - `matplotlib`
  - `seaborn`

---

## 📌 Project Steps:

### 1️⃣ Load and Inspect Dataset
- Uploaded and loaded using `pandas`
- Displayed first few rows using `df.head()`

### 2️⃣ Data Cleaning
- Selected relevant columns
- Dropped rows with missing critical data
- Converted date column to `datetime`

### 3️⃣ Data Visualizations:
#### 📌 Top 10 Countries by Total Cases
- Bar chart using `seaborn` to show countries with the highest COVID-19 cases.

#### 📈 New Cases Trend for India
- Line plot showing daily new COVID-19 cases in India over time.

#### 📊 Total Deaths vs. Total Cases (Top 10 Countries)
- Comparative bar chart for total cases and deaths.

#### 📈 Growth Trend for India
- Line plot showing growth of total cases over time.

#### 💀 Death Rate by Country (Bonus)
- Calculated using:  
  `death_rate = (total_deaths / total_cases) * 100`
- Bar chart of top 10 countries with highest death rate.

---

## 📸 Sample Visualizations:

> 📌 Include screenshots or output charts here (optional but recommended)

---

## 📁 File Structure:

