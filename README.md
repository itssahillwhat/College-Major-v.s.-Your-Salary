# College-Major-v.s.-Your-Salary

## Project Overview

This project explores the relationship between college majors and salary outcomes using data from PayScale Inc.'s year-long survey of 1.2 million Americans holding only a bachelor's degree. The analysis aims to answer several key questions about the financial returns of different college majors.

## Key Questions

- Which degrees have the highest starting salaries?
- Which majors have the lowest earnings after college?
- Which degrees have the highest earning potential?
- What are the lowest risk college majors from an earnings standpoint?
- Do business, STEM (Science, Technology, Engineering, Mathematics), or HASS (Humanities, Arts, Social Science) degrees earn more on average?

## Learning Outcomes

By working through this project, you will learn:

- How to explore a Pandas DataFrame
- How to detect and handle NaN (not a number) values
- How to select specific columns, rows, and individual cells in a DataFrame
- How to sort data within a DataFrame
- How to group data by categories for analysis

## Instructions

1. **Explore the DataFrame**: Use `.head()`, `.tail()`, `.shape`, and `.columns` to understand the structure of the DataFrame, including the number of rows and columns and their names.

2. **Handle Missing Values**: Detect NaN values with `.isna()` and clean your data using `.dropna()`.

3. **Select Data**: Access entire columns with `df['column name']` or multiple columns with `df[['column1', 'column2']]`. Access individual cells using `df.loc[index, 'column name']`.

4. **Analyze Data**: Find the largest and smallest values using `.max()`, `.min()`, `.idxmax()`, and `.idxmin()`. Sort the DataFrame with `.sort_values()` and add new columns with `.insert()`.

5. **Group Data**: Create Excel-style pivot tables by grouping entries with the `.groupby()` method.

## Repository Contents

- `College-Major-v.s.-Your-Salary.ipynb`: Jupyter notebook containing the analysis and visualizations.
- `data.csv`: The dataset containing salary information for different college majors.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/itssahillwhat/College-Major-v.s.-Your-Salary.git
    ```
2. Navigate to the project directory:
    ```bash
    cd College-Major-v.s.-Your-Salary
    ```
3. Install the required dependencies:
    ```bash
    pip install pandas jupyter
    ```
4. Open the Jupyter notebook:
    ```bash
    jupyter notebook Major Salary Analysis.ipynb
    ```

## Conclusion

This project provides insights into how different college majors impact earning potential. By analyzing the data, you can make more informed decisions about education and career paths based on financial outcomes.


## Acknowledgements

- Data source: PayScale Inc.
- Inspiration: Exploring data to make informed educational and career decisions.
