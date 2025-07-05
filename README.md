# 🔥 Analyzing Forest Fire Data using R

This project explores forest fire incidents and their severity using a dataset of fire occurrences. The goal is to identify when most fires happen, what variables affect the fire size (`area`), and how to improve visualizations by handling outliers.

## 📁 Project Structure

- `forestfires.csv` – The dataset containing fire incidents, weather data, and area burned.
- `forest_fire_analysis.Rmd` – R Markdown file containing the full analysis and visualizations.
- `README.md` – This file.

## 🚀 What I Did

- 🧹 **Data Cleaning & Preprocessing:**  
  Converted `month` and `day` to ordered factors so they plot properly.

- 📊 **Exploratory Data Analysis:**  
  - Found that most fires occurred in **August** and **September**, with a small spike in **March**.  
  - Fires were more common during **weekends**.

- 🔍 **Severity Analysis:**  
  - Explored how features like temperature, humidity, wind, and rainfall affect fire area.  
  - Used `facet_wrap()` to compare variables visually.

- ⚠️ **Outlier Handling:**  
  - Identified and removed extreme outliers in `area` that distorted the plots.

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
