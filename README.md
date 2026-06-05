# NJHousingMarketScrape
This project analyzes housing affordability across New Jersey by combining housing market, income, and rental data from multiple public data sources. The goal is to evaluate how housing prices have changed over time relative to wages and household income, and to identify counties experiencing the greatest affordability challenges.

Data Sources
U.S. Census Bureau ACS API
Median Household Income
Median Home Value
Median Gross Rent
Poverty Statistics
County-Level Demographic Data
Federal Reserve Economic Data (FRED)
New Jersey Housing Price Index (NJSTHPI)
Mortgage Rate Data
Economic Indicators
Dataset Construction

Raw API responses were cleaned and transformed into structured Pandas DataFrames. Census variable codes were mapped to descriptive column names, missing values were handled, and additional affordability metrics were created.

# Challenges Encountered
Census data fields use coded variable names that required mapping and documentation.
Data originated from multiple APIs with different formats and structures.
Economic indicators operate on different time scales and frequencies.
Missing values required validation and cleaning.
API rate limits and response formatting required additional handling.

# Project Limitations
Analysis is limited to New Jersey counties.
County-level averages may not reflect individual household situations.
Mortgage rates, homeowner insurance, and property taxes are not directly incorporated into affordability calculations.
Some economic variables are available only at the state level.
Housing affordability is influenced by factors beyond those included in the dataset.
