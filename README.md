# World Layoffs Data Analysis

This project involves Exploratory Data Analysis (EDA) on a dataset containing information about global layoffs. The primary aim is to clean and analyze the data to uncover trends, patterns, and insights about layoffs across different companies, locations, and industries.


## Introduction

The purpose of this project is to perform exploratory data analysis on the world layoffs dataset to understand the impact of layoffs globally. This includes identifying the companies with the highest layoffs, understanding the percentage of layoffs, and analyzing trends over time.

## Dataset

The dataset used in this project is `world_layoffs.layoffs_staging2`, which contains information on layoffs across various companies worldwide, which is the continuation of my previous project of data cleaning using MySQL.

Note that data is already cleaned and stored in a staging table which i will be using to perform EDA. Check my World_layoffs_Data_Cleaning repo for the final cleaned data set.

Key columns include:
- `company`: Name of the company
- `total_laid_off`: Total number of people laid off
- `percentage_laid_off`: Percentage of the workforce laid off
- `funds_raised_millions`: Funds raised by the company in millions
- `location`: Location of the company
- `country`: Country of the company
- `date`: Date of the layoff
- `industry`: Industry of the company
- `stage`: Stage of the company

## EDA Process

### Basic Analysis

- Overview of the dataset to get a general understanding.
- Determining the maximum number of total layoffs.
- Analyzing the percentage of layoffs to see the extent of layoffs in various companies.
- Identifying companies with 100% layoffs and analyzing their characteristics.
- Examining the companies with 100% layoffs ordered by the amount of funds raised to understand the impact on startups and established companies.

### Advanced Analysis

- Identifying companies with the biggest single layoffs.
- Determining companies with the most total layoffs.
- Analyzing layoffs by location to understand geographical impact.
- Summarizing layoffs by country to get a broader regional perspective.
- Examining layoffs by year to identify trends over time.
- Analyzing layoffs by industry to understand which sectors were most affected.
- Summarizing layoffs by company stage to see if certain stages are more vulnerable to layoffs.

### Complex Analysis

- Identifying top companies with the most layoffs per year.
- Calculating the rolling total of layoffs per month to see trends over time.
- Using CTEs (Common Table Expressions) for more complex queries to get deeper insights.

## Insights

- Identified companies with the largest single layoffs and total layoffs.
- Discovered trends in layoffs across different locations, countries, industries, and company stages.
- Analyzed layoffs over time to understand the impact year by year and month by month.
- Highlighted companies that went out of business with significant funds raised.

## Technologies Used

- SQL for data querying and analysis
- Database: MySQL

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/sirishaa03/EDA_World_Layoffs.git
    ```
2. Set up the database connection.
3. Run the SQL queries provided in the EDA.sql sheet.


## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.


