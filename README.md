# Greater Sydney Analysis
## Summary
This project analyses various datasets related to Greater Sydney, aiming to evaluate the distribution of resources across businesses, healthcare, education, transportation, and recreational facilities. The analysis provides insights into regional disparities and resource availability to inform local government decision-making. \
[Report.pdf](https://github.com/nith263/greater-sydney-analysis/blob/main/Report.pdf) contains the written analysis for this project. 

## Project Description
The Greater Sydney Analysis project was completed as part of my university coursework, receiving **19/20**. The goal was to assess how well-resourced different regions within Greater Sydney are, focusing on factors such as business presence, healthcare facilities, public transport access, and educational institutions.

## Datasets Used
- **Business.csv:** Data from the Australian Bureau of Statistics on businesses categorised by industry and SA2 regions.
- **Stops.txt:** Location of transportation methods (buses, ferries, trains) in GTFS format from Transport for NSW.
- **Population.csv:** Population data by age for SA2 regions from the Australian Bureau of Statistics.
- **PollingPlaces.csv:** Locations of polling places for the 2019 Federal Election from the Australian Electoral Commission.
- **Catchments:** Data on catchment regions for primary and secondary schools from the NSW Department of Education.
- **Incomes:** Total earnings by SA2 regions from the Australian Bureau of Statistics.
- **Crimes:** Crime data by suburb from Sydney Suburb Reviews.
- **Playgrounds:** List of playgrounds and fitness centres within the region from The City of Sydney.

## Methodology
1. Data Collection & Pre-processing:
    - Extracted and cleaned data from multiple sources to ensure consistency and accuracy.
    - Merged datasets based on common identifiers (e.g., SA2 codes) using SQL for querying.

2. Analytical Techniques:
    - Calculated Z-scores to assess resource availability in different regions.
    - Applied the sigmoid function to derive a comprehensive resource availability score.

3.  Visualisation:
    - Created various visualisations (heatmaps, boxplots) to illustrate findings and correlations between different factors.

## Key Findings
Identified [number]% of regions as under-resourced based on analysis of business and healthcare availability.
Discovered minimal correlation between median income levels and resource distribution across regions.
Developed insights that can guide local government in resource allocation and urban planning.

## Technologies Used
**Programming Languages:** Python, SQL
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn
**Tools:** Jupyter Notebook
