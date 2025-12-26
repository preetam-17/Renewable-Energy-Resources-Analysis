# 🌱 Renewable Energy Usage Analysis

## 📌 Project Overview

This project focuses on **analyzing renewable energy adoption and household energy usage patterns** using a structured dataset. The analysis explores how factors such as **energy source type, region, household size, income level, and adoption year** influence monthly energy consumption.

The objective is to **derive insights from renewable energy data using Python-based data analysis and visualization techniques**.

---

## 📂 Dataset Description (`renewable_energy.csv`)
data set path-https://www.kaggle.com/datasets/hajraamir21/global-renewable-energy-usage-2020-2024
The dataset contains household-level renewable energy usage information across multiple regions and years.

### 🔑 Key Features:

| Column Name       | Description                                              |
| ----------------- | -------------------------------------------------------- |
| Energy_Source     | Type of renewable energy used (e.g., Solar, Wind, Hydro) |
| Monthly_Usage_kWh | Monthly energy consumption in kilowatt-hours             |
| Household_Size    | Number of people in the household                        |
| Income_Level      | Income category of the household                         |
| Region            | Geographic region                                        |
| Country           | Country name                                             |
| Year              | Year of data record                                      |
| Adoption_Year     | Year renewable energy was adopted                        |

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas** – Data loading and manipulation
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Interactive analysis environment

---

## 🔍 Project Workflow

### 1️⃣ Data Loading

* Imported the dataset using `pandas.read_csv()`
* Converted raw data into a DataFrame for analysis

### 2️⃣ Exploratory Data Analysis (EDA)

* Viewed dataset structure using `head()`, `tail()`, `info()`, `describe()`
* Checked:

  * Missing values
  * Duplicate records
  * Data types
  * Dataset size and shape

### 3️⃣ Statistical Analysis

* Calculated:

  * Mean and median monthly energy usage
  * Energy source distribution
  * Income level distribution
  * Adoption trends over years
* Grouped data by:

  * Household size
  * Region
  * Country

### 4️⃣ Data Visualization

* Line plot showing **Average Monthly Energy Usage by Region and Year**
* Trend analysis of renewable energy adoption
* Comparison of energy usage across household sizes

---

## 📊 Key Insights

* Certain regions show **higher renewable energy usage trends over time**
* Household size has a **direct impact on monthly energy consumption**
* Adoption of renewable energy has **increased steadily across years**
* Solar energy appears as one of the **most commonly used renewable sources**
* Income level influences renewable energy adoption patterns

---

## 📁 Project Structure

```
Renewable-Energy-Analysis/
│
├── renewed_energy.ipynb
├── renewable_energy.csv
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook

```bash
jupyter notebook renewed_energy.ipynb
```

---

## 🎯 Use Cases

* Renewable energy trend analysis
* Household energy consumption studies
* Academic projects (MCA / BCA / Data Analytics)
* Beginner to intermediate data analysis portfolio project


