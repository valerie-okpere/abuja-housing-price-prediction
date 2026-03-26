# Abuja Housing Market: A Linear & Ridge Regression Analysis

This project applies concepts from the **World Quant University program** to a real-world housing dataset, focusing on **Abuja, Nigeria**. Using data cleaning, visualization, and machine learning techniques, I implemented a **Ridge Regression model** to predict housing prices and explore how key property features influence market value.

---

## 📌 Project Overview

The goal of this project was to understand the Abuja housing market by analyzing over **24,000 property listings**. The workflow included:

1. **Data Wrangling:** Filtering to Abuja listings, converting numeric columns, removing outliers, and preparing the dataset for modeling.
2. **Exploratory Data Analysis (EDA):** Visualizations such as histograms, boxplots, and scatter plots to explore distributions and relationships between features and price.
3. **Correlation Analysis:** Evaluating the relationships between price and numeric features like bedrooms, bathrooms, and toilets.
4. **Machine Learning:**

   * Built a **baseline model** using the mean price.
   * Implemented a **Ridge Regression pipeline** with one-hot encoding for categorical variables.
   * Evaluated performance using **Mean Absolute Error (MAE)** on training and test sets.
5. **Interactive Predictions:** A Jupyter Notebook widget allows users to adjust property features and get real-time price predictions.

* **Dataset Source:** [Kaggle - Nigeria Houses and Prices Dataset](https://www.kaggle.com/datasets/abdullahiyunus/nigeria-houses-and-prices-dataset)
* **Original Data Source:** [Nigeria Property Centre](https://nigeriapropertycentre.com/)

---

## 📊 Dataset Description

The dataset contains **24,326 entries** with 8 key parameters. For this project, only **2020 listings within Abuja** were considered.

| Parameter         | Description                                        |
| :---------------- | :------------------------------------------------- |
| **Bedrooms**      | Number of bedrooms in the house                    |
| **Bathrooms**     | Number of bathrooms                                |
| **Toilets**       | Number of toilets                                  |
| **Parking Space** | Available parking slots                            |
| **Title**         | The type of house (e.g., Terrace, Detached Duplex) |
| **Town**          | Neighborhood/location within Abuja                 |
| **State**         | State (filtered to Abuja)                          |
| **Price**         | Market value of the property (target variable)     |

---

## 🔍 Key Findings

* **Bedrooms, bathrooms, and toilets** show positive correlations with price.
* Ridge regression outperforms the baseline mean model on training and test sets.
* The model allows for **interactive price predictions**, enabling users to explore the impact of various features on housing prices in Abuja.

---

## 🚀 Getting Started

You can explore the full workflow, including data preprocessing, visualizations, model building, and interactive predictions, in the repository:

* **GitHub:** [Nigerian Real Estate Project](https://github.com/Abdulkbk/Nigerian-Real-Estate-Project)  
  *(Don’t forget to ⭐ the repo!)*

**Setup:**

1. Clone the repository.
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn category_encoders ipywidgets
3. Open the Jupyter Notebook to run the interactive analysis and prediction widgets.

## Contact & Connect

Author: Abdullahi Yunus

LinkedIn: linkedin.com/in/abdullahi-yunus-0894351a
Email: abdoollahikbk@gmail.com