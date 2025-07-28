# Analysing Dead Age Difference Between Left-handedness and Right-handedness

## Context:
This project, completed during an internship provided by MedTourEasy, required a strong foundation in Python programming. It is a data analysis project, heavily relying on the pandas, numpy, and matplotlib libraries.

## Project Overview:
This project investigates the potential difference in average age at death between left-handed and right-handed individuals. It involves analyzing death rate data and handedness prevalence to calculate and compare the average lifespan of these two groups. The analysis considers data from different study years (e.g., 1990 and 2018) to observe any shifts in trends.

## Key Features:
* **Data Loading and Preprocessing**: Reads and filters death rate data, and handedness prevalence from CSV files (e.g., `dod.csv`, `lh.csv`).
* **Probability Calculation**: Implements functions to calculate the probability of death at various ages for both left-handed and right-handed populations, conditioned on specific study years.
* **Average Age at Death Computation**: Calculates the weighted average age at death for each handedness group by summing the product of ages and their corresponding probabilities.
* **Comparative Analysis**: Determines the difference in average age at death between left-handed and right-handed individuals for specified study years.
* **Data Visualization**: Utilizes matplotlib to generate plots illustrating the overall death age distribution by handedness, providing a visual representation of the findings.

## Libraries Used:
* **pandas**: For data manipulation and analysis.
* **numpy**: For numerical operations, especially in probability calculations and handling of `NaN` values.
* **matplotlib.pyplot**: For creating static, interactive, and animated visualizations in Python.

## How to Run:
The project is implemented as a Jupyter Notebook (`Analysis_death_age_difference_of_Righthanded_with_Lefthanded.ipynb`). To run this project:
1.  Ensure you have Python installed along with the required libraries (pandas, numpy, matplotlib).
2.  Open the `.ipynb` file using Jupyter Notebook or JupyterLab.
3.  Run the cells sequentially to execute the data analysis and view the results, including the calculated average ages at death and the generated plots.

## Conclusion:
The project provides insights into the potential disparity in lifespan based on handedness, presenting calculated average death ages and their differences for various study years.
