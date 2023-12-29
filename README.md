# Practice with Python

Welcome to the "python-practice" repository! This is a space where I explore and practice basic data analysis using Python, with a focus on essential tools like Pandas, Matplotlib, and Seaborn.

## Overview

In this repository, you'll find Jupyter Notebooks showcasing fundamental data analysis tasks, including data cleaning, exploration, and visualization. The primary libraries used are:

- [Pandas](https://pandas.pydata.org/): Data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/): Basic and advanced data visualizations.
- [Seaborn](https://seaborn.pydata.org/): Statistical data visualization built on Matplotlib.

## Dataset Source

The data used in this analysis is sourced from the UNdata, WorldBank and IMF websites. It provides information about world's GDP per capita as of 2021, covering all data available from the three sources for 223 territories and countries. It's important to note that the figures presented here may be subject to variations due to factors such as exchange rate fluctuations and differing costs of living.

## EDA (Exploratory Data Analysis)

I started by using some basic functions offered by pandas to analyse the dataframe (called df for simplicity), such as:

- **df.info()** to obtain a concise summary of the data frame with data types and missing values;
- **df.shape** to see the dimensions of the data frame with insights about the number of rows and columns;
- **df.value_counts()** to explore the distribution of unique values in specific columns, offering a quick overview of categorical data;
- **df.describe()** to generate descriptive statistics, including measures of central tendency and dispersion, for numerical columns;
- **df.head()** to display the initial rows of the dataframe, gaining a snapshot of the dataset's structure and content;
- **df.tail()** to view the last rows, ensuring a complete understanding of the dataset;
- **df.sample(5)** to obtain a random sample of 5 rows, offering a representative subset of the data for exploration.





