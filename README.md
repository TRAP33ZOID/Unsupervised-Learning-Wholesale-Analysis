# Unsupervised-Learning-Wholesale-Analysis 

This project aims to analyze the purchasing behavior of clients of a wholesale distributor. The dataset contains annual spending in monetary units on diverse product categories.
Project Structure:

    Data Import:
        Loaded the dataset into Python for analysis.

    Data Cleaning:
        Checked for missing or erroneous data.
        Imputed missing values and corrected obvious errors.

    Exploratory Data Analysis (EDA):
        Generated summary statistics for each column.
        Visualized data distributions, relationships, and correlations.
        Detected and handled outliers.

    KMeans Clustering:
        Preprocessed the data.
        Determined the optimal number of clusters.
        Performed KMeans clustering to segment the data.

    Hierarchical Clustering:
        Visualized the hierarchical structure using a dendrogram.
        Extracted clusters from the hierarchical structure.

    Principal Component Analysis (PCA):
        Performed PCA to identify the underlying structure of the data.
        Analyzed which combinations of features best describe the customers.

Key Findings:

    Customer Segmentation: KMeans clustering identified two main groups of customers with distinct purchasing patterns.
    Hierarchical Structure: Hierarchical clustering revealed a clear data structure with potential for multi-level analysis.
    PCA Insights: A few principal components explained a significant portion of the variance, indicating feature redundancy.
    Correlations: Some product categories, like "Grocery" and "Detergents_Paper", showed strong correlations, indicating co-purchasing trends.

Conclusions:

The analyses provided insights into customer purchasing behaviors, offering valuable information for targeted marketing, inventory management, and other business strategies.
