# Overlook Here's When We Expect Omicron to Peak

**Overview**
This project focuses on cleaning and visualizing COVID-19 data using Python and Tableau. It processes weekly case data, extracts key insights, and creates meaningful visualizations to analyze trends over time.

**Project Structure**
``` 
├── Bad Visualization book.twb   # Tableau workbook with visualizations
├── covid.ipynb                  # Jupyter Notebook for data cleaning and transformation
├── all_cases.xlsx               # Processed data output for Tableau
├── weekly_cases.csv             # Original raw dataset
```

**Data Processing**
Input Data:

- weekly_cases.csv: The original dataset containing weekly COVID-19 case counts.

Data Cleaning and Transformation:

- covid.ipynb:

    - Cleans the raw dataset
    - Generates monthly average case counts
    - Extracts the first available record of each month
    - Creates Line Chart for each monthly average case counts and first    available record of each month
    - Creates a new structured dataset suitable for Tableau visualization

Output Data:

- all_cases.xlsx: A cleaned and structured dataset prepared for use in Tableau.


**Visualization**
Bad Visualization book.twb: Tableau workbook containing visualizations of COVID-19 trends from 2020 to 2022.
- adjust the True/False drop-down button to toggle between displaying all data and showing data in seven-day intervals

# Getting Started
**Prerequisites**
- Python 3.x
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn (for data processing and visualization)
- Tableau (for visualization)

**Running the Project**

1. Clone this repository:

git clone 
```
https://github.com/miffycheng/Overlook-Here-Is-When-We-Expect-.git
```

2. Navigate to the project directory:
```
cd yourrepository
```
3. Open and run the Jupyter Notebook
4. Load ```all_cases.xlsx``` into Tableau and use ```Bad Visualization book.twb``` for analysis

This project is for educational purposes. Feel free to use and modify it as needed.

Author
Miffy C.
