# Advertising Sales Analysis and Statistical Modeling

This project explores the relationship between various advertising media channels and product sales. It utilizes exploratory data analysis (EDA), implements a multiple linear regression model, and performs statistical hypothesis testing to validate experimental results.


## Project Structure

### 1. Data Analysis and Sales Prediction
The primary objective of this section is to develop a model that predicts sales based on advertising spend across TV, Radio, and Newspaper.

**Dataset Overview:**
- **Source**: `data.csv`
- **Observations**: 200 entries
- **Features**: `tv`, `radio`, `newspaper` (Advertising budget)
- **Target**: `sales`

**Methodology:**
* **Data Preprocessing**: Verified data integrity by checking for missing values and duplicate rows (none were found).
* **Exploratory Data Analysis (EDA)**: Visualized feature distributions using histograms to understand the variance in advertising spend across different media.
* **Regression Modeling**: A Multiple Linear Regression model was built using the `statsmodels` library.
* **Performance Metric**: The model was evaluated using the **Mean Absolute Percentage Error (MAPE)**.
    * **Result**: The model achieved a **MAPE of approximately 6.42%**, indicating high predictive accuracy.

### 2. Statistical Hypothesis Testing
This section focuses on rigorous statistical testing to compare experimental data against theoretical expectations.

**Key Components:**
* **T-Statistics**: Calculated T-values for experimental results (e.g., $t = 1.64$).
* **Probability Density Functions (PDF)**: Utilized `scipy.stats` to model distributions and determine the likelihood of observed outcomes.
* **Significance Testing**: Evaluated experimental values against critical thresholds to confirm or reject hypotheses regarding the data.

## Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Matplotlib**: Data visualization and plotting.
- **Statsmodels**: Statistical modeling and regression.
- **SciPy**: Advanced statistical functions and probability distributions.

## How to Run
1. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib statsmodels scipy
    ```

2. Place the data.csv file in the same directory as the notebook.

3. Launch Jupyter Notebook and run sales_analysis_regression.ipynb.