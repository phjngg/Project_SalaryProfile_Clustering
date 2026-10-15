# Salary Profile Clustering

Unsupervised learning project for identifying salary groups across three datasets using K-Means and Hierarchical Clustering.

## Project Overview
This project compares clustering approaches across three salary datasets:
- Degrees That Pay Back
- Salaries by College Type
- Salaries by Region

The objective was to identify meaningful salary profiles and study how clustering results change across different algorithms and configurations.

## Methods
### K-Means
Experiments included:
- Number of clusters
- Initialization method
- Number of initializations

### Hierarchical Clustering
Experiments included:
- Number of clusters
- Linkage method
- Distance metric

## Evaluation
Clustering performance was evaluated using:
- Silhouette Score
- Sum of Squared Errors (SSE)
- Normalized Mutual Information (NMI) for datasets with reference categories

## Results
Hierarchical Clustering produced stronger cluster separation than K-Means across all three datasets.

Example:
- Degrees That Pay Back
  - K-Means Silhouette = 0.4577
  - Hierarchical Silhouette = 0.4802

Hierarchical Clustering with Ward linkage and Euclidean distance was selected as the final model for this dataset.

## Tools
- Python
- pandas
- NumPy
- scikit-learn

## Key Learning
This project strengthened my understanding of:
- unsupervised learning
- cluster evaluation
- model selection
- K-Means initialization
- linkage methods
- distance metrics
- interpreting cluster profiles
