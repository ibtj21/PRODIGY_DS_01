___
# PRODIGY_DS_01
### Distribution of Categorical and Continuous Variables - Visualization
# Table of Contents
1. [Description](#description)
2. [Overview](#overview)
3. [Data Source](#data-source)
4. [Installation](#installation)
5. [Usage](#usage)
    - [Data Preprocessing and Analysis](#data-preprocessing-and-analysis)
    - [Visualization and Interpretation](#visualization-and-interpretation)
6. [Contributors](#contributors)
7. [Contributing](#contributing)
8. [License](#license)

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

To get started with the project, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/ibtj21/PRODIGY_DS_01.git
    ```

2. Navigate to the project directory:
    ```bash
    cd PRODIGY_DS_01
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

The `requirements.txt` file includes the following dependencies:

- pandas
- plotly
- seaborn
- matplotlib
___

## Usage

1. Load the dataset into a pandas DataFrame.
2. Clean the dataset by removing duplicates and unnecessary columns.
3. Visualize categorical and continuous variables, focusing on insights from gender, marital status, age, and weekly work hours.

### Data Preprocessing and Analysis
- **Data Cleaning**: Remove duplicates to ensure data accuracy.
- **Subset Selection**: Focus on `sex`, `marital-status`, `age`, and `hours-per-week` for targeted analysis.

### Visualization and Interpretation
1. **Categorical Variables**: Visualize gender and marital status distributions using bar charts.
2. **Continuous Variables**: Analyze age and hours-per-week distributions using histograms and other plots.
___
## Contributors
- Hanna Hailemarima Gashaw
___
## Contributing
Contributions are welcome! To contribute:

- Fork the repository.
- Create a new branch (e.g., `feature/your-feature`).
- Commit your changes.
- Submit a pull request.

Ensure your changes align with the project's coding standards.
___

## License
## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/ibtj21/PRODIGY_DS_01/blob/main/LICENSE) file for more details.
