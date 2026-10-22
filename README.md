# Avocado Price Effect Analysis 🥑📉

A fun, exploratory data analysis project designed to visually and mathematically prove the economic "Price Effect" (the inverse relationship between price and demand). 

By analyzing historical avocado sales data, this project demonstrates how increases in the average price of conventional avocados lead to a measurable drop in total sales volume.

## The Process
This experiment relies on a standard Python data science stack to walk through four logical steps:
1. **Data Loading:** Reading historical sales data into a structured Pandas DataFrame.
2. **Control Filtering:** Isolating 'conventional' avocados across the 'TotalUS' region to create a clean, apples-to-apples economic environment.
3. **Visualization:** Drawing a downward-sloping regression line through a scatter plot of Price vs. Volume to visually indicate the price effect.
4. **Mathematical Proof:** Running an Ordinary Least Squares (OLS) linear regression to calculate the exact negative correlation and generate a p-value for statistical significance.

## Tech Stack
* **Python 3**
* **Pandas** (Data manipulation)
* **Matplotlib & Seaborn** (Data visualization and trendlines)
* **Statsmodels** (OLS regression math and statistical summaries)

## How to Run This Project
1. Clone this repository to your local machine.
2. Download the [Avocado Prices dataset from Kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices).
3. Extract the `avocado.csv` file and place it in the same directory as the Jupyter Notebook.
4. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn statsmodels
   ```
5. Open `price_effect.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially.

## Future Explorations
This baseline model can easily be modified to test other variables, such as comparing price sensitivity in specific cities (e.g., Los Angeles vs. Chicago) or analyzing the elasticity of 'organic' buyers versus 'conventional' buyers.
