
# 1. Why make_classification Has the Constraint n_classes * n_clusters_per_class <= 2^n_informative
 - When using make_classification, each cluster (a group of data points) must be linearly separable from the others using only the informative features provided.
 - With n_informative features, you can separate the feature space into at most 2^n_informative linearly separable regions 