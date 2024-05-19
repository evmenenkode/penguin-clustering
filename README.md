# Penguin Clustering Project
This project involves clustering a dataset of penguins based on their physical characteristics using Principal Component Analysis (PCA) and K-Means clustering. The dataset used is the Palmer Archipelago (Antarctica) penguin dataset.

## Project Overview
The project performs the following tasks:

1. Data Cleaning: Removing rows with missing values and identifying outliers.
2. Exploratory Data Analysis: Visualizing distributions of key variables using boxplots.
3. Data Preprocessing: Standardizing the data and converting categorical variables to numerical format.
4. Principal Component Analysis: Reducing the dimensionality of the data.
5. K-Means Clustering: Grouping the penguins into clusters based on the PCA-transformed data.
6. Analysis: Calculating and displaying the mean values of key characteristics for each cluster.
## File Descriptions
- penguins.csv: The dataset containing penguin measurements.
- penguin_clustering.jpynd: The main script that performs data cleaning, EDA, PCA, clustering, and analysis.
- README.md: This file, which provides an overview of the project.
## Data Cleaning
- Rows with missing values are removed.
- Outliers in the flipper_length_mm column are identified using the IQR method and removed.
## Exploratory Data Analysis (EDA)
- Boxplots are generated for culmen_length_mm, culmen_depth_mm, flipper_length_mm, and body_mass_g.
## Data Preprocessing
- Categorical variables are converted to dummy variables.
- Features are standardized using StandardScaler.
## Principal Component Analysis (PCA)
- PCA is applied to reduce the dimensionality of the dataset.
- The explained variance ratio of each principal component is plotted to help decide the number of components to retain.
## K-Means Clustering
- The Elbow method is used to determine the optimal number of clusters.
- K-Means clustering is performed on the PCA-transformed data.
- The resulting clusters are visualized and the centroids are highlighted.
## Analysis
- The mean values of key characteristics (culmen_length_mm, culmen_depth_mm, flipper_length_mm) are calculated and displayed for each cluster.

## Results
The project outputs visualizations of the data, including boxplots and PCA explained variance. It also generates a plot showing the K-Means clusters and their centroids. Additionally, it prints out the mean values of key characteristics for each cluster.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.
