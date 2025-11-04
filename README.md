# cars-details-analysis
Exploratory data analysis of car specifications from `cars.csv` using Python to uncover patterns in performance, efficiency, and design.

# 🚗 Car Dataset Analysis using Python

This repository contains exploratory data analysis (EDA) performed on the `cars.csv` dataset, which includes specifications for various car models. The goal of the analysis is to uncover patterns in fuel efficiency, engine design, and performance based on different vehicle attributes.

Two Jupyter Notebooks are included:

* – Focuses on visualizations and descriptive statistics.
* – Includes deeper insights, comparisons, and visual storytelling.

---

## 📁 Dataset Overview

The `cars.csv` file contains the following columns:

| Column  | Description                              |
| ------- | ---------------------------------------- |
| `model` | Car model name                           |
| `mpg`   | Miles per gallon (fuel efficiency)       |
| `cyl`   | Number of cylinders                      |
| `disp`  | Engine displacement (cu. inches)         |
| `hp`    | Gross horsepower                         |
| `drat`  | Rear axle ratio                          |
| `wt`    | Weight (1000 lbs)                        |
| `qsec`  | 1/4 mile time                            |
| `vs`    | Engine type (0 = V-shaped, 1 = straight) |
| `am`    | Transmission (0 = automatic, 1 = manual) |
| `gear`  | Number of forward gears                  |
| `carb`  | Number of carburetors                    |

---

## 🔍 Analysis Performed

The notebooks perform a comprehensive EDA process using Python (Pandas, NumPy, Matplotlib, Seaborn). Key analysis steps include:

* **Data inspection and cleanup**

  * Checked for missing values and data types.
  * Renamed ambiguous columns and converted categorical variables.
* **Statistical summary**

  * Descriptive statistics for all numeric columns.
  * Correlation matrix to examine relationships between variables.
* **Visualizations**

  * Histograms for understanding distribution of `mpg`, `hp`, `wt`, etc.
  * Boxplots to compare `mpg` across transmission and cylinder types.
  * Pair plots and heatmaps for multivariate analysis.
  * Bar plots showing transmission preference across models.

---

## 💡 Insights Gained

From the analysis, several interesting observations emerged:

* **Fuel Efficiency (`mpg`)**:

  * Cars with **fewer cylinders** tend to be more fuel efficient.
  * Manual transmission cars (`am = 1`) generally show **higher mpg** compared to automatic ones.
  * Lighter cars (`wt`) show a clear positive trend with higher mpg.

* **Horsepower (`hp`) vs. Weight (`wt`)**:

  * Heavier cars tend to have more horsepower, indicating a possible trade-off between power and fuel economy.

* **Transmission Trends**:

  * Manual cars often outperform automatic ones in terms of fuel efficiency and acceleration (lower `qsec`).

* **Correlations**:

  * `wt`, `hp`, and `disp` are strongly negatively correlated with `mpg`.
  * `gear`, `am`, and `drat` have weaker but interesting relationships with performance metrics.

* **1/4 Mile Time (`qsec`)**:

  * Cars with higher horsepower do not always perform better; weight and transmission significantly influence acceleration.

---

## 🧰 Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 File Descriptions

* Initial analysis, feature descriptions, and basic plots.
* Advanced EDA with visualizations and detailed comparison of fuel economy, transmission, and performance.

---

## 📈 Conclusion

This project provides a foundational understanding of how various car specifications impact fuel efficiency and performance. The insights gained here could guide decisions in automotive design, marketing, and consumer education.

---
