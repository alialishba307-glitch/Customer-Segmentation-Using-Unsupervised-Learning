# Customer-Segmentation-Using-Unsupervised-Learning

## Task Objective

The objective of this project is to segment customers based on their spending behavior using unsupervised learning techniques. By identifying distinct customer groups, the goal is to help businesses design targeted marketing strategies and improve customer engagement.

## Approach

The project follows a structured data science workflow:

## Data Understanding & Exploration

Loaded and inspected the Mall Customers dataset.
Analyzed key features such as Age, Annual Income, and Spending Score.
Performed exploratory data analysis (EDA) to understand customer distribution and behavior patterns.

## Data Preprocessing

Selected relevant features for clustering (e.g., income and spending score).
Standardized data to ensure equal importance of features.

## Clustering (K-Means)

Applied the Elbow Method to determine the optimal number of clusters.
Trained the K-Means clustering model.
Assigned cluster labels to each customer.

## Dimensionality Reduction
Applied PCA (Principal Component Analysis) for visualization.
Optionally used t-SNE for improved cluster visualization.

## Visualization & Interpretation
Visualized clusters using scatter plots.
Interpreted customer segments based on behavioral patterns.

## Results & Insights

Customers were successfully segmented into distinct groups based on income and spending behavior.
Clear separation between high spenders and low spenders was observed.
Some clusters represented high-income but low-spending customers, indicating potential marketing opportunities.
Dimensionality reduction techniques helped visualize cluster separation effectively.

## Business Insights

High-income, high-spending customers should be targeted with premium products and loyalty programs.
Low-income, high-spending customers may respond well to discounts and promotional offers.
High-income, low-spending customers represent an opportunity for targeted marketing campaigns to increase engagement.
Low-income, low-spending customers may require cost-effective marketing strategies.

## Conclusion

This project demonstrates how unsupervised learning can be used to uncover hidden patterns in customer data. By applying K-Means clustering and visualization techniques, meaningful customer segments were identified. These insights can support more effective marketing strategies and improved customer targeting.

## Future Improvements

Use advanced clustering techniques such as DBSCAN or Hierarchical Clustering.
Incorporate additional features such as purchase history or frequency.
Experiment with t-SNE for better non-linear visualization.
Deploy clustering results into a recommendation system.

## Tools & Technologies


Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

PCA / t-SNE

Jupyter Notebook
