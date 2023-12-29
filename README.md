# Practice with Python

Welcome to the "python-practice" repository! This is a space where I explore and practice basic data analysis using Python, with a focus on essential tools like Pandas, Matplotlib, and Seaborn.

## Overview

In this repository, you'll find Jupyter Notebooks showcasing fundamental data analysis tasks, including data cleaning, exploration, and visualization. The primary libraries used are:

- [Pandas](https://pandas.pydata.org/): Data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/): Basic and advanced data visualizations.
- [Seaborn](https://seaborn.pydata.org/): Statistical data visualization built on Matplotlib.

## Dataset Source

The data used in this analysis is sourced from the UNdata, WorldBank and IMF websites. It provides information about world's GDP per capita as of 2021, covering all data available from the three sources for 223 territories and countries. It's important to note that the figures presented here may be subject to variations due to factors such as exchange rate fluctuations and differing costs of living.

## EDA (Exploratory Data Analysis) with Pandas

### Data Overview
I started by using some basic functions offered by pandas to analyse the dataframe (called df for simplicity), such as:
- **df.info()** to obtain a concise summary of the data frame with data types and missing values;
- **df.shape** to see the dimensions of the data frame with insights about the number of rows and columns;
- **df.value_counts()** to explore the distribution of unique values in specific columns, offering a quick overview of categorical data;
- **df.describe()** to generate descriptive statistics, including measures of central tendency and dispersion, for numerical columns;
- **df.head()** to display the initial rows of the dataframe, gaining a snapshot of the dataset's structure and content;
- **df.tail()** to view the last rows, ensuring a complete understanding of the dataset;
- **df.sample(5)** to obtain a random sample of 5 rows, offering a representative subset of the data for exploration.

### Statistical Analysis
Some other steps included checking for missing values using **df.isnull()**, removing some records using the **df.drop()** function, before performing some statistical data analysis using:
- **df.mean()** to calculate the mean of numerical columns, providing insights into central tendencies;
- **df.max()** to identify the maximum values in each column, offering an understanding of data ranges;
- **df.nlargest()** to retrieve the top N largest values, facilitating the identification of extreme values or outliers;

Other functions used include **df.loc**, **df.idmax**, **df.unique**, **df.sort_values()**, **df.groupby**, **df.reset_index** and more.

## Data Visualization with Matplotlib (plt) and Seaborn (sns)

### Visualizations Created
Some of the visualization created:

- **Histograms** using **df.hist()**;
- **Correlation Heatmaps** using **sns.heatmap(corr)**; 
- **Subset Correlation Heatmap** using **subset_df.corr()**;
- **Barplot** using **sns.barplot()**;
- **Scatter Plot** using **df.plot()**;
- **Boxplot** using **sns.boxplot()**;

The boxplot helped to identify outliers, which were subsequently removed for a more accurate analysis. Outliers can significantly impact statistical measures and distort the interpretation of results.



