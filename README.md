# Exploratory Data Analysis on Cricket Player Statistics

This repository contains the code and data for an exploratory data analysis (EDA) project on cricket player statistics. In this project, we imported data from the website ESPN Cricinfo using HTML scraping and conducted various data cleaning and analysis tasks to answer specific questions.

## Project Details
###Data Collection
The data was obtained by importing the web content from the provided URL using HTML scraping. The imported data included the webpage's writings and logo, which were manually removed to extract the relevant information. The cleaned data was then structured into a table and saved as a CSV file for further analysis.

### Data Cleaning
Upon initial inspection of the data, several data cleaning tasks were performed:

1. Setting Correct Column Names: The data had unnamed headers, and the actual column headers were in the 14th row. Correct column names were set.

2. Handling Null Values: The first 13 rows contained NaN values, and the last dozen or so rows were also NaN values. These null values were dropped.

3. Removing Duplicates: Any duplicate rows in the dataset were removed.

4. Transforming 'span' Column: The 'span' column was split into two separate columns: Debut Year and Final Year.

5. Extracting Player's Country: The player's country was extracted from their names.

6. Data Type Conversion: All data types were converted to their correct types.

7. Creating Career Length Column: A new column representing career length was created.

## Questions Answered
The following questions were addressed using the cleaned and transformed data:

1. Average Career Length: The average career length of cricketers was calculated to be 12.75 years.

2. Average Batting Strike Rate: For cricketers who played over 10 years, the average batting strike rate was found to be 47.95.

3. Number of Cricketers Before 1960: There were 23 players who debuted before 1960.

4. Maximum Highest Innings Score by Country: The maximum highest innings score by country was determined.

5. Statistics by Country (Hundreds, Fifties, Ducks): The number of hundreds, fifties, and ducks (0) averages were calculated by country.

## Data Files
cricket_player_stats.csv: The cleaned and structured dataset in CSV format.
Usage
You can use the provided dataset and code to perform further analysis or build visualizations based on your specific requirements. Feel free to explore the code in the repository to understand the data cleaning and analysis process.

## Requirements
To run the code and reproduce the analysis, you will need:

Python (recommended version: Python 3)
Required Python libraries (Pandas)

## Author
**Ehsan Nabatchian**


Acknowledgments
Special thanks to ESPN Cricinfo for providing the cricket player statistics data used in this analysis.

