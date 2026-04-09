# Final Cummalative Project for ITCS 3162 at UNC Charlotte - Contribution Log
Project Title: Wellness Grocery Inventory Analysis
Group 29 | Course: Introduction to Data Mining

## 1. Contribution Log
This log tracks the primary responsibilities and contributions of each team member throughout the project lifecycle.

| Member Name | Key Responsibilites | Deliverables/Nodes Owned | Percentage Effort |
| --- | --- | --- | --- |
| Minh Nguyen | Team Lead and Visualization | Histogram, Box Plot, PCA, Scatter Plot (PCA) | 50% |
| Krish Iyer | Fairness and Model Architect  | Scatter Plot Matrix, k-Means, UWW Kmeans Clustering, Line Plot, Color Manager, Scatter Plot (Javascript) (legacy) | 50% |

## 2. Version Control & Infrastructure
Primary Communication Platform: Discord

Weekly Sync Time: Monday 8 AM - 9 AM

GitHub Repository Link: https://github.com/nguyennminh/ITCS-3162-Project

## 3. Workflow Documentation
KNIME Workflow Overview: A brief description of the final pipeline.

Key Annotations: 
  - Chosen 3 Features, KiloCalories, Water, Fat Total Lipids based off of correlation matrix using the Scatter Plot Matrix node.
  - After aplying PCA and identifying the dimensions using a Scatter Plot node we concluded that it has high variance overall. The data spreads much more along the horizontal axis than the vertical axis showing that the first PCA dimension captures most of the variance. A few outlier points far from main cluster also add extra spread to overall data.
  - Based off of the visualization from Line Plot node with the elbow method from using the UWW KMeans Clustering node to get the WCSS for each k, we can see that when k = 6 threshold point in which after that point the WCSS is not significantly changing anymore making it the elbow point. This shows that k = 6 is the most optimal k.

Known Limitations: [Students: List any issues or edge cases the model does not handle well]

## 4. Group Agreement & Attestation
By signing below, all team members confirm that the work contained within this repository is the result of a collaborative effort and that all individual contributions are fairly represented in the log above.

Member 1 : Minh Nguyen Date: March 27, 2026

Member 2 : Krish Iyer Date: March 27, 2026
