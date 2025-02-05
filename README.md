# Clustering Results

This document presents the results of clustering analysis using different techniques and data preprocessing methods.

## K-Means Clustering Results

### No Data Processing
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.174466   | 136.674065        | 1.690472      |
| 4        | 0.190545   | 136.108490        | 1.480735      |
| 5        | 0.188296   | 134.064355        | 1.389558      |

### Using Normalization
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.174466   | 136.674065        | 1.690472      |
| 4        | 0.190986   | 136.221537        | 1.482004      |
| 5        | 0.188311   | 133.993363        | 1.385375      |

### Using Transform
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.184227   | 142.482152        | 1.685186      |
| 4        | 0.187092   | 137.842444        | 1.530177      |
| 5        | 0.191315   | 136.889557        | 1.376939      |

### Using PCA
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.343051   | 405.367021        | 0.919147      |
| 4        | 0.338763   | 438.087470        | 0.878220      |
| 5        | 0.329847   | 418.191987        | 0.907417      |

### Using T+N
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.174853   | 136.368549        | 1.722694      |
| 4        | 0.190569   | 136.111604        | 1.481578      |
| 5        | 0.189124   | 134.136016        | 1.367854      |

### T+N+PCA
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.351282   | 426.551537        | 0.914205      |
| 4        | 0.346891   | 459.042034        | 0.873686      |
| 5        | 0.346615   | 441.559263        | 0.879335      |

## Hierarchical Clustering Results

### No Data Processing
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.149245   | 116.890908        | 1.843427      |
| 4        | 0.134960   | 107.901135        | 1.641375      |
| 5        | 0.131054   | 104.773051        | 1.535168      |

### Using PCA
| Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|----------|------------|-------------------|---------------|
| 3        | 0.303353   | 350.000801        | 1.037257      |
| 4        | 0.270510   | 322.707847        | 0.964873      |
| 5        | 0.267302   | 335.386461        | 0.924378      |

## MeanShift Clustering Results

(No results provided for MeanShift Clustering)

This document provides a structured view of the clustering results, allowing for easy comparison between different preprocessing techniques.

