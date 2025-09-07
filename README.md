# 🐉 Pokémon Data Analysis with Pandas

## 📌 Project Overview

This project explores the **Pokémon dataset** using **Python (pandas, matplotlib, seaborn)** to extract insights about Pokémon attributes, strengths, and trends. The goal is to demonstrate **data cleaning, exploratory data analysis (EDA), feature engineering, and visualization** techniques commonly used in data analysis projects.

## 📂 Dataset

The dataset used is **`pokemon_data.csv`**, which contains attributes such as:

* **Name** – Pokémon name
* **Type 1, Type 2** – Primary and secondary types
* **Stats** – HP, Attack, Defense, Sp. Atk, Sp. Def, Speed
* **Generation** – Which generation the Pokémon belongs to
* **Legendary** – Boolean indicating if the Pokémon is legendary


## ⚙️ Steps in the Analysis

### 1. Data Loading & Inspection

* Loaded CSV into pandas DataFrame
* Checked dataset shape, column info, and summary statistics

### 2. Data Cleaning

* Handled missing values and duplicates
* Standardized column names for easier analysis

### 3. Exploratory Data Analysis (EDA)

* **Categorical Insights**: Distribution of Pokémon types, generations, and legendary counts
* **Numerical Insights**: Top Pokémon by Attack, Defense, and Speed
* **Grouped Insights**: Average stats by type, legendary vs. non-legendary comparison

### 4. Feature Engineering

* Created **Total Stats** by summing all base stats
* Added **Strong Pokémon Flag** (Pokémon with total stats > 500)

### 5. Visualization

* Distribution plots for Attack, Defense, and Speed
* Count plots of Pokémon by Type and Generation
* Correlation heatmap of numerical features
* Boxplots comparing Legendary vs. Non-Legendary Pokémon

### 6. Exporting Results

* Saved cleaned dataset as `pokemon_data_cleaned.csv`
* Exported grouped insights (e.g., average stats by type)


## 📊 Key Insights

* **Dragon-type Pokémon** tend to have higher overall stats.
* **Legendary Pokémon** outperform regular ones in almost all attributes.
* **Generation 1** Pokémon dominate in frequency but not always in strength.
* Speed and Attack show strong variance across different Pokémon types.


## 🚀 Tech Stack

* **Python**
* **Pandas** – Data cleaning & analysis
* **Matplotlib & Seaborn** – Visualization


## 📌 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/shankarnarayananiyer/pokemon-data-analysis.git
   cd pokemon-data-analysis
   ```
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook pokemon_analysis.ipynb
   ```



## 📈 Future Improvements

* Build a **classification model** to predict if a Pokémon is Legendary based on stats.
* Create interactive dashboards using **Plotly or Power BI**.
* Extend analysis with **battle simulations** or type effectiveness.



## ✨ Author

👤 **Shankar Narayanan Iyer**

* 📍 Nuremberg, Germany
* 🎯 Data Analyst | SQL | Python | Power BI | Pandas | Tableau
* 💼 Looking for roles in Business/Data Analysis in Germany

