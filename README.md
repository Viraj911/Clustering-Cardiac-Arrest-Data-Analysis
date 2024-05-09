# Clustering-project

# Health Risk Prediction: Clustering Analysis

## Project Overview
This project involves a comprehensive analysis of a health dataset containing various attributes such as gender, smoking habits, tobacco consumption, blood pressure, obesity, diabetes, and metabolic syndrome. The goal is to identify patterns and clusters within the data to predict health risks accurately.

## Part 1: Data Exploration and Pre-processing

### Steps Undertaken:
1. **Load Dataset**: The dataset was loaded into the working environment.
2. **Check Null Values**: We performed a null value analysis to ensure data integrity.
3. **Dataset Information**: Information about the dataset's structure was printed.
4. **Statistical Description**: The dataset was described in statistical terms to understand the distribution of data.
5. **Drop 'Under Risk' Column**: The 'Under Risk' column was dropped as per the project requirements.

## Part 2: Working with Models

### Clustering Analysis:
1. **K-Means Clustering**: We applied K-Means clustering to the pre-processed dataset.
2. **Cluster Centers**: The centers of the clusters were identified and printed.
3. **Cluster Column**: A new column for predicted label values was created.
4. **Hierarchical Clustering**: Hierarchical clustering was visualized using `scipy`.
5. **Agglomerative Clustering**: This clustering technique was applied with a specified number of clusters.
6. **Label Column**: A column for the predicted cluster labels was created.
7. **Label Counts**: The counts of each label were displayed.
8. **Silhouette Score**: The silhouette score was calculated to evaluate the clustering performance.

## Results and Discussion
The clustering techniques provided insights into the dataset, revealing distinct groups based on health risk factors. The silhouette score indicated the effectiveness of the clustering.

## Conclusion
The analysis successfully segmented the dataset into meaningful clusters, which can be used to predict health risks and inform healthcare strategies.

## How to Use
Instructions on how to run the analysis in a local environment can be included here.

## Dependencies
List of libraries and tools required to run the project.

## Authors
- Viraj Panchal

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Mention any collaborators or data sources here.
