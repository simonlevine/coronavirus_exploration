# coronavirus_exploration
Clustering analysis and classification of coronavirus sequence data and metadata (work in progress).

1) Clustering novel and other coronavirus strains by k-mer tokenized sequence data, reduced to 2 dimensions by PCA, by K-Means and Spectral Clustering (sklearn).
2) Classifying (~650) novel coronavirus sequences by geographic origin using the dimensionality-reduced k-mer counts as features and geography of sampling as labels.
3) Classifying (~3,000) sequences of the coronaviridae taxon across hosts, timepoints, and strains, with dimensionality-reduced k-mer counts as features and geography of sampling as labels.
4) Same as 3), but using fewer classes.
