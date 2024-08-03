# PRODIGY_DS_02
# Titanic Dataset Analysis

This repository contains a detailed analysis of the Titanic dataset from Kaggle. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization to identify patterns and trends in the data.

## Table of Contents

- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
  - [Handling Missing Values](#handling-missing-values)
  - [Converting Data Types](#converting-data-types)
  - [Removing Duplicates](#removing-duplicates)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Summary Statistics](#summary-statistics)
  - [Data Visualization](#data-visualization)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this analysis is the Titanic dataset from Kaggle. It contains information about the passengers aboard the Titanic, including their age, sex, passenger class, and whether they survived the disaster.

## Data Cleaning

### Handling Missing Values

- Missing values in the `Age` column are filled with the median age.
- Missing values in the `Embarked` column are filled with the mode.
- The `Cabin` column is dropped due to too many missing values.

### Converting Data Types

- The `Sex` column is converted to numerical values (0 for male, 1 for female).
- The `Embarked` column is converted to numerical values (0 for C, 1 for Q, 2 for S).

### Removing Duplicates

- Duplicate rows, if any, are removed from the dataset.

## Exploratory Data Analysis (EDA)

### Summary Statistics

Summary statistics are provided to give an overview of the dataset, including measures such as mean, median, and standard deviation.

### Data Visualization

Several visualizations are created to explore the relationships between variables:

- Distribution of Age
- Survival Rate by Sex
- Survival Rate by Passenger Class
- Correlation Heatmap

## How to Run

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/titanic-analysis.git
    cd titanic-analysis
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the analysis script:
    ```sh
    python analysis.py
    ```

## Dependencies

- pandas
- matplotlib
- seaborn

You can install the dependencies using the command `pip install -r requirements.txt`.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
