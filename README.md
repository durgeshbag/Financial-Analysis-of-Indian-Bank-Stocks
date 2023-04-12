
# Financial Analysis of Indian Bank Stocks

The "Financial Analysis of Indian Bank Stocks" project is a data analysis project that utilizes Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn. 

The project aims to analyze the financial performance of different Indian banks by studying their stock prices in the past decade 2012-2022 and uncovers major events happened during this period.




## Project Overview

Stocks chosen for analysis includes top private banks such as HDFC, IDFC bank. and also public banks such as PNB, YES bank were deliberately chosen to identify past scams in them.

The project collects historical stock prices of Indian banks from reliable sources, such as Yahoo Finance. The collected data is cleaned, processed, and transformed using Pandas and NumPy, which are powerful data manipulation and numerical computing libraries in Python.


To find the performance of stocks, a returns dataframe was created which uses the pct_change method to get single day change of stock prices.


The project then uses Matplotlib and Seaborn, which are data visualization libraries, to create charts, graphs, and plots that help illustrate trends and patterns in the data. These visualizations can be used to identify potential investment opportunities or to gain insights into the performance of different banks.


Some of the visualizations include pairplot betweeen price percentage changes, distribution charts, prices to date chart, Moving average of prices for technical analysis, heatmap of the correlation between the stocks close price, seaborn's cluster map to cluster the correlations together.
 

Finally, the project provides a comprehensive analysis of the data, including key statistics and trends in the stock prices of Indian banks. The analysis includes parameters such as the maximum and minimum close prices observed during the period, the average return on stocks, the total volume traded, and the standard deviation on returns.
## Project Stages
The project involved several stages:

1. Data Collection: Historical stock prices of Indian banks were collected from reliable sources, such as Yahoo Finance.

2. Data Cleaning and Processing: The collected data was cleaned, processed, and transformed using Pandas, which is a powerful data manipulation library in Python. NumPy, a numerical computing library, was used to perform mathematical operations on the data, such as calculating stock returns, standard deviations, and correlations.

3. Exploratory Data Analysis: The project utilized Matplotlib and Seaborn, data visualization libraries, to create charts, graphs, and plots that help illustrate trends and patterns in the data.

4. Data Analysis: The project provided a comprehensive analysis of the data, including key statistics and trends in the stock prices of Indian banks. The analysis included parameters such as the maximum and minimum close prices observed during the period, the average return on stocks, the total volume traded, and the standard deviation on returns.
## Tools Used
The following tools were used for this project:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn



## Output
The output of the project included various charts and graphs illustrating the performance of each bank's stock, as well as tables summarizing the key financial metrics. The output provided valuable insights into the performance of different banks.

Some uncertainaties were observed in YES bank and PNB bank. The best bank to invest came out to be HDFC bank. Result also revealed stock market crashes in covid pandemic 2020, Demonetization 2017 etc .


Above information can help investors make informed decisions about their investments to stay up-to-date with the latest trends in the Indian banking industry.
## Setup and Installation

To run this project, follow these steps:

1. Clone the repository to your local machine using the following command:

```bash
  git clone https://github.com/durgeshbag/Financial-Analysis-of-Indian-Bank-Stocks.git

```
2. Install the required libraries using pip:

```bash
  pip install numpy pandas matplotlib seaborn
```
3. Run the Jupyter notebook to execute the code:

```bash
  jupyter notebook Financial-Analysis-of-Indian-Bank-Stocks.ipynb
```
## Conclusion
Overall, this project demonstrates how Python libraries can be used to perform financial analysis and gain insights into the performance of Indian banks based on various parameters. The analysis can be useful for investors looking to make informed decisions about their investments in the Indian banking industry.