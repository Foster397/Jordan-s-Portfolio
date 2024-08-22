Data Analytics Portfolio

# [Project 1: Kansas City Crime vs Housing Prices](https://github.com/Foster397/Portfolio?tab=readme-ov-file#portfolio-project)

### This project was built using Excel, BigQuery (SQL), and Tableau.

My wife and I have been casually looking for houses in our free time but are not always able to tell if the neighborhood is safe.
So, as part of my portfolio build, I decided to make something that would be useable to us while we looked at houses and neighborhoods. 

1. The housing data was scraped on 07/26/2024 and only represents houses on the market at that time.
   * All unnecessary, redundant, or null data was removed.
   * Some columns were rearranged to enhance the readability and function of the data.
   * I removed unnecessary heading tags from the column names.
   *  Unmatching data types were corrected (such as some property sizes being recorded in sqft and others in acres).

2. The crime data was found at [Open Data KC](https://data.kcmo.org/Crime/KCPD-Crime-Data-2023/bfyq-5nh6/about_data)
   * This data is the full report from 2023 data. 
   * Dates and times were split into separate columns to preserve the data integrity when importing into BigQuery.
   * A 'category' column was added to categorize the crimes into four simple labels.
   * About 16,000 records were removed either because of incomplete data or the crimes were traffic-related and therefore
   don't accurately account for the amount of crime in a certain zip code.

### The visual I made for this project can be found on [Tableau](https://public.tableau.com/app/profile/jordan.foster7733/viz/KansasCityCrimevsHousingPrices/Dashboard1)

#### All of the code and files can be found on the linked repository. 
