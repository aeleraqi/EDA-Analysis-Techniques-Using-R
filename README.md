# 🚢 Titanic Dataset Exploratory Data Analysis (EDA) with R

[![R](https://img.shields.io/badge/Language-R-blue.svg)](https://www.r-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a case study showcasing how to apply Exploratory Data Analysis (EDA) techniques on the Titanic dataset using R. The analysis includes data exploration, handling missing values, data transformations, and visualizations.

## 📂 File Structure

- **`Ttanic_R_EDA.pdf`**: A detailed case study that walks through applying various EDA techniques to the Titanic dataset using R.
- **`Titanic EDA R Code`**: The code used in this analysis is embedded within the PDF. You can extract and run it in your R environment.

## 📊 Data Source

The Titanic dataset used in this analysis is publicly available and can be accessed via:
- [Titanic Dataset on GitHub](https://github.com/aeleraqi/EDA-Analysis-Techniques-Using-R/blob/main/titanic.csv)

## 🛠️ Analysis Techniques

The following EDA techniques are demonstrated in the study:

1. **Data Importing**: Methods to import the dataset into R using RStudio's "Import Data" feature.
2. **Exploratory Functions**:
   - `View()`, `head()`, `tail()` for exploring the dataset.
   - `dim()` for checking the dataset dimensions.
   - `names()`, `str()` for understanding the structure and columns of the dataset.
3. **Handling Missing Values**:
   - `na.omit()` to remove rows with missing values.
   - Replacing missing values in the Age column with the mean.
4. **Transforming Variables**: 
   - Conversion of categorical variables (`Survived`, `Pclass`, `Sex`) into factors.
5. **Subsetting Data**: Filtering data based on conditions like survival status and ticket class.

## 📈 Data Visualization

Various visualizations are created to explore the Titanic dataset, including:
- **Histograms**: Age distribution of passengers, survivors, and non-survivors.
- **Bar Plots**: Distribution of ticket classes among survivors and non-survivors.
  
## 💻 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Titanic_R_EDA.git
   cd Titanic_R_EDA
