# 🌸 K-MEANS VS. BISECTING CLUSTERING (IRIS DATA)

Goal: Compare Flat K-Means ($k=3$) and Bisecting K-Means ($K=3$) on standardized Iris data.

Methodology: Standardized features, iterative K-Means for $k$ selection, and custom Bisecting implementation (2 splits).

Key Finding (Alignment): Both methods resulted in identical cluster assignments (approx 0.62), showing equal alignment with true species labels.

## Structural Insight:

Setosa is the most distinct group, separated first (highest Delta SSE).

Versicolor/Virginica are the overlapping groups, separated last (lowest $\Delta$SSE and negative silhouette points).

Centroids: Final three clusters are highly interpretable, matching the small, medium, and large flower archetypes.
