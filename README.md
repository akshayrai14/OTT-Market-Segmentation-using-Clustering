# Demographic Segmentation for OTT Viewer Clustering

This project focuses on demographic segmentation for Over-the-Top (OTT) platforms using clustering techniques. It analyzes the population, age, gender, employment status, and potential viewership across different U.S. states. By utilizing K-means, Hierarchical (Birch and Agglomerative), and Spectral clustering, the research identifies unique demographic clusters that can help optimize marketing and content strategies for OTT platforms.

## Overview

### Objective: 
To identify key viewer segments based on demographics and their potential viewership across various U.S. states.
### Methodology: 
Clustering techniques (K-means, Hierarchical, Spectral) are applied to group states based on demographic similarities. The analysis investigates the factors that most influence viewership within each cluster.
### Tools & Technologies: 
Python, scikit-learn, pandas, numpy, matplotlib, seaborn, Elbow Method for optimal clustering, and visualization techniques for data interpretation.
### Key Insight: 
Identifying demographic patterns in viewer preferences to drive marketing and content strategies.

## Table of Contents

- Installation
- Usage
- Research Paper
- Technologies Used
- Clustering Techniques
- Results and Findings
- License

## Installation

1. ***Clone the repository:***
   
```bash
git clone https://github.com/yourusername/ott-viewer-segmentation.git
cd ott-viewer-segmentation
```

2. ***Install required dependencies:***
   
```bash
pip install -r requirements.txt
```

## Usage

- Load the dataset that includes demographic data and viewer potential for each state.
- Use the clustering.py script to perform clustering on the dataset.
- The Elbow Method will be applied for K-means clustering to determine the optimal number of clusters.
- After clustering, explore the demographic features of each cluster to identify key insights on viewership.
- Use visualization tools (matplotlib, seaborn) to create graphs and plots for deeper analysis.
  
#### Example:

```bash
python clustering.py
```

## Research Paper

For a detailed explanation of the methodologies, results, and analysis, you can access the full research paper at the following link:

[Research Paper](https://doi.org/10.35940/ijisme.F9862.12050524)

## Technologies Used
1. **Programming Language:** Python
2. **Libraries:** scikit-learn (for clustering), pandas (for data manipulation), numpy (for numerical operations), matplotlib (for data visualization), seaborn (for enhanced data visualization)

## Clustering Techniques

This project employs the following clustering algorithms to analyze the viewer data:

- K-means Clustering : A centroid-based algorithm that partitions the data into a predefined number of clusters (k).
- Birch Clustering: A variation of hierarchical clustering optimized for large datasets.
- Agglomerative Clustering: Builds a hierarchy from bottom to top, merging the closest clusters.
- Spectral Clustering : Uses graph theory to cluster data points based on similarity. This technique can capture more complex structures within the data.

### Other Methods:

- Elbow Method (for optimal K-means clustering)
- Linkage Adjustment Techniques (for clustering validation)


## Results and Findings

The analysis revealed the following **demographic clusters**:

 :orange_circle: **Cluster 1:** High concentration of younger male viewers. <br>
 :orange_circle: **Cluster 2:** Predominantly older female viewers. <br>
 :orange_circle: **Cluster 3:** A balanced mix with regional variations in viewership preferences.
  
Key demographic groups, such as age, gender, and employment status, significantly influenced viewership patterns within each cluster.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
