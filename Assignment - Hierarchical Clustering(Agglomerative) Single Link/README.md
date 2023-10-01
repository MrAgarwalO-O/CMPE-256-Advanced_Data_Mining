
# Hierarchical Clustering (Agglomerative) - Single Link

This repository contains a pdf file - "Hierarchical Clustering(Agglomerative) Single Link". This file contains all the calculations and the step by step process of creating clusters in multiple iterations. It includes the calculation of the ecludian distance, initial matrix, distance matrix and all the minimum distance points.
<br><br>This repository also contains a Jupyter notebook "Clustering" that contains the program to show the Hierarchical Clustering, specifically the agglomerative clustering technique. The notebook focuses on three linkage methods:

1. **Single Link**
2. **Complete Link**
3. **Average Link**

## Background
Hierarchical Agglomerative clustering starts with treating each observation as an individual cluster, and then iteratively merges clusters until all the data points are merged into a single cluster. Dendrograms are used to represent hierarchical clustering results.

## Data Points

The notebook uses a set of predefined data points in 2D space. Each point is labeled with a letter, from 'A' to 'K'.<br>
'A': (2, 2)<br>
'B': (2, 6)<br>
'C': (3, 7)<br>
'D': (5, 2)<br>
'E': (5, 5)<br>
'F': (5, 8)<br>
'G': (6, 6)<br>
'H': (7, 3)<br>
'I': (8, 4)<br>
'J': (10, 6)<br>
'K': (12, 8)

## Implementation

The notebook starts by installing and importing the required libraries, including `matplotlib`, `numpy`, and `scipy`. The main steps include:

1. Visual representation of the given data points.
2. Application of the single-link clustering method and visual representation of the resulting dendrogram.
3. Application of the complete-link clustering method and visual representation of the resulting dendrogram.
4. Application of the average-link clustering method and visual representation of the resulting dendrogram.

## Results

The notebook provides visual outputs (dendrograms) for each linkage method, to understand the clustering structure.

## References
https://www.analyticsvidhya.com/blog/2021/06/single-link-hierarchical-clustering-clearly-explained/<br>
https://medium.com/@MaheshGadakari/hierarchical-agglomerative-clustering-hac-with-single-linkage-method-1159fa623d52<br>
https://www.youtube.com/watch?v=YH0r47m0kFM<br>
https://www.youtube.com/watch?v=RdT7bhm1M3E&t=529s<br>
https://statsandr.com/blog/clustering-analysis-k-means-and-hierarchical-clustering-by-hand-and-in-r/#single-linkage-1

