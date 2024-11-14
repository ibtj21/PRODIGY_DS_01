___
# PRODIGY_DS_01
### Distribution of Categorical and Continuous Variables - Visualization
Table of Contents
___
## Description
This project focuses on visualizing the distribution of categorical and continuous variables in the Adult (Census Income) dataset. Variables such as gender, marital status, age, and weekly work hours are highlighted, and insights about demographic and socio-economic trends in the dataset are uncovered through these visualizations.
___
## Overview
Using Python libraries like pandas, seaborn, and plotly, this project presents a detailed distribution analysis of select categorical and continuous variables. The analysis includes both static and interactive visualizations to highlight patterns and proportions within the dataset. The project targets both gender and marital status (categorical) distributions and age and hours-per-week (continuous) distributions.
___

## Data Source

The dataset used in this project is the [Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset) available on Kaggle.
___
## Installation
Ensure the following libraries are installed before running the code:
```bash
pip install pandas seaborn matplotlib plotly
```

## Usage
To visualize the dataset, follow these steps:
1. Load the dataset into a pandas DataFrame.
2. Clean the dataset by removing duplicates and unnecessary columns.
3. Generate the visualizations as outlined below.

## Data Preprocessing and Analysis
1. **Data Cleaning**: Remove duplicate entries to ensure accuracy.
2. **Subset Selection**: Focus on `sex`, `marital-status`, `age`, and `hours-per-week` for targeted analysis.

## Visualization and Interpretation

### 1. Distribution of Categorical Variables
- **Gender Distribution**: Bar charts using seaborn and plotly show the proportion of males to females, highlighting a higher representation of males.
- **Marital Status Distribution**: Visualizations reveal the most common marital statuses, with "married-civ-spouse" and "never-married" being the largest groups.

### 2. Distribution of Continuous Variables
- **Age Distribution**: Histograms show a predominance of individuals in their 20s to 40s, tapering off in older age groups.
- **Hours-Per-Week Distribution**: Analysis reveals common work-hour ranges, showing peak distributions around the standard 40-hour workweek.

## Contributors
- [Your Name]

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.
