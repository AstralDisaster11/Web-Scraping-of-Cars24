# Web-Scraping-of-Cars24

This project focuses on analyzing scraped data from Cars24, specifically targeting Hyundai, Kia, and Nissan cars. The data was cleaned, merged, and analyzed to derive insights, such as the distribution of prices and the impact of fuel type on car prices. The project also includes exploratory data analysis (EDA) with visualizations.

# Features
Data Loading: Loaded datasets for Hyundai, Kia, and Nissan cars.
Data Cleaning: Handled missing values, removed duplicate rows, and converted price data into numerical format.
Merging Datasets: Combined the individual datasets into a single dataframe for further analysis.
Exploratory Data Analysis (EDA): Conducted visualizations to understand price distributions, fuel types, and the relationship between kilometers driven and car prices.
Descriptive Statistics: Provided insights into the overall dataset.

# Dataset
The project uses the following datasets:
Hyundai_cars_data.csv: Dataset for Hyundai cars.
Kia_cars_data.csv: Dataset for Kia cars.
Nissan_cars_data.csv: Dataset for Nissan cars.
The datasets contain various features related to car specifications, including the price, fuel type, kilometers driven, and more.

# Requirements
Python 3.x
Libraries:
NumPy
Pandas
Matplotlib
Seaborn

# Project Workflow

Data Loading:
Loaded the Hyundai, Kia, and Nissan car datasets using Pandas.

Data Exploration:
Displayed the first few rows and shapes of each dataset.
Merged the three datasets into one combined dataset.

Data Cleaning:
Checked for missing values and dropped rows with missing data.
Checked for and removed duplicate rows to ensure data quality.
Cleaned the 'Price' column by removing unwanted symbols (₹, L) and converting it into numeric format.

Descriptive Statistics:
Provided summary statistics like mean, standard deviation, and more to understand the data.

# Exploratory Data Analysis (EDA):

Visualized the distribution of car prices using histograms.
Analyzed the distribution of fuel types using count plots.
Created boxplots to analyze the relationship between fuel type and price.
Generated scatterplots to study the correlation between kilometers driven and price.
Example Visualizations
Price Distribution: A histogram of car prices after cleaning the data.
Fuel Type Distribution: A count plot showing the distribution of cars by fuel type.
Price vs. Fuel Type: A boxplot displaying the relationship between fuel type and price.
Price vs. Kilometers Driven: A scatter plot showing the correlation between kilometers driven and car prices, colored by fuel type.
