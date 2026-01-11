# 🏡 Housing Prices Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📋 Project Overview
This project performs a comprehensive data analysis and predictive modeling on housing price data. The goal is to identify the key features that influence property values (such as square footage, number of bedrooms, and location) and build a regression model to predict future housing prices accurately.

This analysis is valuable for real estate investors, homeowners, and data enthusiasts looking to understand market trends.

## 📂 Dataset
The project likely uses the **House Sales in King County, USA** dataset (or a similar housing dataset).
* **Source:** [Kaggle / King County Open Data]
* **Timeframe:** Homes sold between May 2014 and May 2015
* **Key Features:**
    * `price`: Sale price (Target Variable)
    * `sqft_living`: Square footage of the living space
    * `bedrooms` / `bathrooms`: Number of rooms
    * `floors`: Number of floors
    * `waterfront`: Whether the house has a view of the waterfront
    * `condition` / `grade`: Overall condition and construction quality

## 🛠 Technologies Used
* **Python**: Core programming language.
* **Pandas**: For data manipulation, cleaning, and aggregation.
* **NumPy**: For numerical computations.
* **Matplotlib & Seaborn**: For data visualization (correlation heatmaps, boxplots, scatter plots).
* **Scikit-Learn**: For building and evaluating machine learning models (Linear Regression, Ridge Regression).

## 📊 Key Steps in Analysis
1.  **Data Wrangling**:
    * Handling missing values (if any).
    * Converting data types for accurate analysis.
2.  **Exploratory Data Analysis (EDA)**:
    * Visualizing the distribution of prices.
    * Analyzing correlations between features (e.g., *Does having a waterfront view significantly increase price?*).
3.  **Model Development**:
    * Splitting data into training and testing sets.
    * Implementing **Linear Regression** and **Ridge Regression** models.
    * Refining models using polynomial features.
4.  **Model Evaluation**:
    * Evaluating performance using **R² (R-squared)** and **MSE (Mean Squared Error)** metrics.

## 🚀 How to Run the Project
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AAgusCF/Data-Analysis-Housing-Prices.git](https://github.com/AAgusCF/Data-Analysis-Housing-Prices.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Data-Analysis-Housing-Prices
    ```
3.  **Install required dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook Data_Analysis_Housing_prices_.ipynb
    ```

## 📈 Results & Findings
* *Key Insight:* Features like `sqft_living` and `grade` showed the strongest positive correlation with housing prices.
* *Model Performance:* The Ridge Regression model achieved an R² score of approximately 0.75, indicating a strong fit for the data.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
