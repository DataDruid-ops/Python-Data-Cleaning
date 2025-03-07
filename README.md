# FIFA 21 Player Data Analysis

## Project Overview
This project focuses on analyzing FIFA 21 player data to extract meaningful insights. The dataset used contains detailed information about players, including their clubs, contracts, and performance metrics. The project aims to clean the data, explore various attributes, and extract contract-related information.

## Dataset
- **File Name:** `fifa21 raw data v2.csv`
- **Description:** This dataset contains FIFA 21 player information, including their club affiliations, contract details, and performance stats.

## Requirements
To run this project, you need the following dependencies:

```python
pip install pandas numpy
```

## Steps in the Project
1. **Importing Libraries**
   - `pandas` for data manipulation
   - `numpy` for handling missing values

2. **Reading the Dataset**
   - The dataset is loaded using `pandas.read_csv()`.
   - Display options are set to view all columns.

3. **Exploratory Data Analysis (EDA)**
   - Checking the shape of the dataset.
   - Displaying general dataset information using `.info()`.

4. **Data Cleaning**
   - Creating a copy of the dataset.
   - Stripping whitespace from club names.
   - Extracting unique club names.

5. **Handling Contract Information**
   - Identifying players who are `On Loan` or `Free Agents`.
   - Developing a function to extract contract details such as start date and end date.

## Usage
- Run the script in a Python environment to analyze FIFA 21 player data.
- Modify the dataset processing logic as needed to extract additional insights.

## Future Work
- Expand contract analysis to include duration calculations.
- Perform deeper statistical analysis on player performance metrics.
- Visualize key insights using Matplotlib or Seaborn.

## Author
This project is developed as part of a data analysis exercise. Contributions and improvements are welcome!


