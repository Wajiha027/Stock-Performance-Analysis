# Stock Performance Analysis

## Overview
This project analyzes stock performance data, identifies similar stock behaviors, determines unique patterns, and distinguishes stocks that move together from those that do not. The project involves data preprocessing, dimensionality reduction, clustering, and visualization techniques.

## Steps Involved

### Loading the Dataset
- Download and load the dataset containing stock prices and the S&P 500 index.

### Data Preprocessing
- Handle missing values by filling them with the mean of the respective columns.
- Normalize the data to ensure all features contribute equally to the analysis.

### Analyzing Stock Performance Similarity
- Use Principal Component Analysis (PCA) to reduce the dimensionality of the dataset and visualize stock performance in a 2D space.

### Identifying Unique Patterns
- Apply KMeans clustering to identify unique patterns in the stock data and count the number of unique clusters.

### Identifying Stocks Moving Together and Differently
- Perform hierarchical clustering on the transposed data to identify which stocks move together and visualize the results using a dendrogram.

## Files
- **data_stocks.csv**: The dataset used for analysis. [Download from Google Drive](https://drive.google.com/file/d/19qCpap5IkpdF504nlrlCgni34Ba0pJLx/view?usp=sharing)
- **stock_analysis.ipynb**: Jupyter Notebook with code and explanations.
- **README.md**: Project overview and instructions.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
