
# Customer Segmentation Project

## Overview

This project aims to analyze customer data and identify distinct customer segments based on their annual income and spending score. The analysis involves data loading, exploration, visualization, scaling, and clustering using the KMeans algorithm.

## Files

- **Customers.csv**: Dataset containing customer information.
- **Customer_Segmentation.ipynb**: Jupyter Notebook containing the code for data analysis and segmentation.

## Libraries Used

- `numpy` for numerical operations.
- `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `mpl_toolkits` for additional tools in plotting.
- `MinMaxScaler` from `sklearn.preprocessing` for feature scaling.

## Tasks

### Task 1: Data Loading & Exploration

- Loaded the dataset using `pd.read_csv`.
- Renamed the 'Genre' column to 'Gender'.
- Checked the shape of the dataframe (200 rows, 5 columns).
- Checked the data types of each column.
- Checked for any missing values (none found).
- Dropped the 'CustomerID' column as it does not contribute to the analysis.

### Task 2: Scatter Plot

- Created a scatter plot between 'Annual Income' and 'Spending Score' to visualize the distribution of customers.

### Task 3: Scaling

- Performed feature scaling using `MinMaxScaler` to bring all features to a common scale.

### Task 4: Clustering with KMeans

- Utilized the KMeans algorithm to develop clusters based on customer features.
- Applied the algorithm to the scaled data.
- Visualized the clusters on the scatter plot.

## Usage

1. Install the required libraries using: `pip install numpy pandas matplotlib seaborn scikit-learn`.
2. Open the `Customer_Segmentation.ipynb` notebook in Jupyter or any compatible environment.
3. Execute the cells in sequential order to reproduce the analysis.

Feel free to modify the code to suit your needs or explore additional analyses.

Happy clustering!
