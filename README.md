# Wine Data Clustering Analysis

## Overview

This project focuses on analyzing hierarchical clustering techniques applied to the Wine dataset. The primary objectives include comparing different linkage methods, observing distance values during cluster merges, and evaluating clustering solutions against K-means clustering.

## Tasks Completed

1. **Comparison of Hierarchical Structures**  
   - Implemented and compared hierarchical clustering using three linkage methods: single linkage, complete linkage, and group average. The analysis highlights the differences in clustering outcomes based on the chosen method.

2. **Distance Values Analysis**  
   - For selected hierarchical structures, the set of distance values at which clusters merge was observed. Patterns in these distance values were identified, providing insights into the merging behavior of clusters.

3. **Clustering Solutions Comparison**  
   - Selected various clustering solutions from the hierarchical structures and compared them with K-means clustering solutions (using `KMeans` from the `sklearn.cluster` module). This comparison focused on how well each clustering method captures the inherent class structure of the dataset.

4. **Attribute Subset Analysis**  
   - Different subsets of attributes from the dataset were selected to re-perform hierarchical clustering. The resulting hierarchical structures were compared with the original structures to assess the impact of attribute selection on clustering outcomes.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wine-clustering-analysis.git
   cd wine-clustering-analysis
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis scripts:
   ```bash
   python hierarchical_clustering.py
   python kmeans_comparison.py
   ```

## Results

The results of the analysis, including visualizations and insights, can be found in the `results` directory. Detailed explanations of the findings and comparisons are documented within the scripts.

## Conclusion

This project provides a comprehensive analysis of hierarchical clustering methods applied to the Wine dataset, offering valuable insights into cluster formation and the effectiveness of different clustering techniques.
