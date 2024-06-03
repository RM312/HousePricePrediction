# House Price Prediction

## Project Overview

This project involves predicting house prices based on various features such as size, number of rooms, location, and more. The dataset used for this project is `HousePricePrediction.xlsx`. The aim is to perform data analysis, visualization, and apply machine learning models to predict house prices.

## Dataset

The dataset contains various features about houses, including both numerical and categorical variables. Below are the steps taken to explore and preprocess the dataset:

### Initial Exploration

1. **Loading the Data**:
    - The dataset is loaded using pandas.
    - The first 5 records of the dataset are printed.
    - The shape of the dataset is displayed.

2. **Variable Types**:
    - The dataset is examined to identify categorical, integer, and float variables.
    - The number of variables for each type is printed.

### Data Analysis and Visualization

3. **Correlation Heatmap**:
    - A correlation heatmap is generated for numeric variables after dropping missing values.

4. **Categorical Variables**:
    - The number of unique values in each categorical column is calculated.
    - A bar plot shows the number of unique values for categorical features.
    - Distribution of categorical features is visualized using bar plots for each feature.

### Data Preprocessing

5. **Dropping Columns**:
    - The `Id` column is dropped as it is not needed for the analysis.

6. **Handling Missing Values**:
    - Missing values in the `SalePrice` column are filled with the mean value of the column.
    - Rows with any other missing values are dropped.

## Usage

### Prerequisites

Ensure you have the following libraries installed:

- pandas
- matplotlib
- seaborn
- numpy

You can install these using pip:

```sh
pip install pandas matplotlib seaborn numpy
```

### Running the Analysis

1. Place the `HousePricePrediction.xlsx` file in your working directory.
2. Load the dataset and perform initial exploration.
3. Identify and count the variable types.
4. Generate a correlation heatmap for numeric variables.
5. Calculate the number of unique values for each categorical column and visualize them.
6. Visualize the distribution of categorical features.
7. Drop the `Id` column and handle missing values by filling and dropping as specified.
8. Verify that no missing values remain in the preprocessed dataset.

## Contributing

If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [NumPy](https://numpy.org/)

Thank you for exploring this project!
