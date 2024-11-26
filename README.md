# Unicorn Companies Analysis

This repository contains SQL queries and the slide presentation for the analytical project on 1060 unicorn companies in 46 countries worldwide. This project aims at exploring the answers to the following questions:

1. Which unicorn companies have had the biggest return on investment?
2. How long does it usually take for a company to become a unicorn?
3. Which industries have the most unicorns?
4. Which countries have the most unicorns?
5. Which investors have funded the most unicorns?

### Data

The dataset used in this analysis contains records of 1060 unicorn companies obtained from [data playground](https://www.mavenanalytics.io/data-playground) of Maven Analytics. <br />
Information on the dataset include:

- `Company` : Company name
- `Valuation` : Company valuation in billions of dollars
- `Date Joined` : The date in which the company reached $1 billion in valuation
- `Industry` : Company industry
- `City` : City the company was founded in
- `Country` : Country the company was founded in
- `Continent` : Continent the company was founded in
- `Year Founded` : Year the company was founded
- `Funding` : Total amount raised across all funding rounds in billions (B) or millions (M) of dollars
- `Select Investors` : Top 4 investing firms or individual investors (some have less than 4)

### SQL Queries

- `data_cleaning.sql`: a query for data cleaning
- `data_exploration.sql`: a query for data exploration
- `query_data_visualization.sql`: a query for data visualization in Tableau

## Project Info.

### Data Cleaning

1. Check for duplicates
2. Rename columns where necessary
3. Standardize date format
4. Drop rows with errors
5. Reformat currency values (e.g., $2M => 2,000,000)
6. Generate new columns based on existing column values
7. Delete unused columns

### Data Exploration

1. SQL skills used:
   - Joins
   - Common Table Expressions (CTEs)
   - Windows Functions
   - Aggregate Functions
   - Data Types Conversion
   - Relational operators

2. Which unicorn companies have had the biggest return on investment (ROI)?

   - This query output shows the top 10 companies with the biggest ROI. Zapier achieved the biggest ROI of 3999 percent. Dunamu comes second with 125 percent ROI, and Workhuman is third with 110 percent ROI.
   - Zapier's ROI is significantly high compared to other companies.

3. How long does it usually take for a company to become a unicorn?

   - On average, a company takes about 6 years to become a unicorn.
   - The majority of companies could become a unicorn within 4 to 7 years.

4. Which industries have the most unicorns?

   - Fintech and Internet Software & Services have about 40 percent of total unicorns.
   - The e-commerce industry also has a significant share of unicorns of 10 percent.
   - These figures show the potential of Fintech, Internet software & services, and E-commerce industries.

5. Which countries have the most unicorns?

   - It is interesting (but not surprising) that the United States has the largest share of unicorns.
   - China and India, the countries with the largest share of the world population, have 15 and 6 percent share of unicorns, respectively.

6. Which investors have funded the most unicorns?
   - This query output shows Accel is the top investor who invests in 60 unicorns.
   - Based on this project's scope, Sequoia Capital and Sequoia Capital China are treated as different investors since we will not dive deep into further details.

### Data Visualization

Techniques utilized for data visualization using Tableau:

1. Parameters
2. Top N filters
3. Reference lines
4. Calculated fields

## Results

### Analytical Results

Brief findings of this project are:

1. Zapier has the biggest return on investment.
2. It usually takes about 6 years to become a unicorn.
3. Fintech industry has the most unicorns.
4. The United States has the most unicorns.
5. Accel has funded the most unicorns.

### Acknowledgments

I thank [Maven Analytics](https://www.mavenanalytics.io/) for making the dataset on unicorn companies publicly avaiable.
