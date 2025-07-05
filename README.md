# 🔥 Analyzing Forest Fire Data using R

This project explores forest fire incidents and their severity using a dataset of fire occurrences. The goal is to identify when most fires happen, what variables affect the fire size (`area`), and how to improve visualizations by handling outliers.

## 📁 Project Structure

- `forestfires.csv` – The dataset containing fire incidents, weather data, and area burned.
- `forest_fire_analysis.Rmd` – R Markdown file containing the full analysis and visualizations.
- `README.md` – This file.
- `Rplot*.png` – Plots generated during the project.

## 🚀 What I Did

- 🧹 **Data Cleaning & Preprocessing:**  
  Converted `month` and `day` to ordered factors so they plot properly.

- 📊 **Exploratory Data Analysis:**  
  - Found that most fires occurred in **August** and **September**, with a small spike in **March**.  
  - Fires were more common during **weekends**.

![Fires by Day](plots/Rplot03.png)
![Fires by Month](plots/Rplot04.png)

- 🔍 **Severity Analysis:**  
  - Explored how features like temperature, humidity, wind, and rainfall affect fire area.  
  - Used `facet_wrap()` to compare variables visually.

![Variable Relationship (with Outliers)](plots/Rplot01.png)
![Variable Relationship (outliers removed)](plots/Rplot.png)

- 📉 **Monthly Variable Patterns:**  
  - Checked how variables like temperature, wind, and humidity vary by month.

![Variable Trends over Months](plots/Rplot02.png)

## 🧠 Skills Used

- R programming  
- Data wrangling with `dplyr`  
- Visualization with `ggplot2`  
- Faceted plots  
- Outlier detection and handling  
- Exploratory data analysis (EDA)

## 📦 Libraries Used

```r
library(ggplot2)
library(dplyr)
library(readr)
library(tidyr)
