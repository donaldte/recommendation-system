# recommendation-system
recommendation system

# Here I'm studying recommenation system 

# Requirements 

- python knowledge 
- Base of data manipulation numpy, pandas, csv
- Base of Machine learning and Deep learning 

# Origin of data

Data I'm using to work here come from GoodRead and Amazon 

The link will be here as soon as possible

# Type of recommendation system
  - Memory based recommendation 
  - Model based recommendation
  - Deep learing(neuron) recommendation

# Memory based recommendation 

`Memory-based recommendation systems` rely on historical data to predict future user preferences and generate recommendations. There are three commonly used similarity metrics in memory-based recommendation systems: Jaccard, cosine, and Pearson. Each metric has its advantages and disadvantages, which can impact the quality and accuracy of recommendations.

`Jaccard similarity` measures the similarity between two sets by computing the ratio of the intersection of the sets to the union of the sets. The advantage of using Jaccard similarity is that it works well for sparse datasets, where there are many missing values. Jaccard similarity can also handle binary data, which is useful when dealing with user-item interactions (i.e., when a user either interacts with an item or does not). However, Jaccard similarity does not take into account the magnitude of the data and is sensitive to noise, which can result in less accurate recommendations. Jaccard similarity is commonly used in collaborative filtering systems.

`Cosine similarity` measures the similarity between two vectors by computing the cosine of the angle between them. The advantage of using cosine similarity is that it is computationally efficient and works well for high-dimensional data. Cosine similarity can handle both binary and non-binary data, making it a versatile similarity metric. However, cosine similarity does not take into account the magnitude of the data and can be biased towards popular items. Cosine similarity is commonly used in content-based recommendation systems.

`Pearson correlation` measures the linear correlation between two variables. The advantage of using Pearson correlation is that it takes into account the magnitude of the data and can handle both positive and negative correlations. Pearson correlation can also handle missing data, making it useful for datasets with many missing values. However, Pearson correlation assumes that the data is normally distributed, which may not always be the case. Pearson correlation is commonly used in collaborative filtering systems.

In general, the choice of similarity metric depends on the nature of the dataset and the recommendation system being developed. For example, Jaccard similarity is commonly used in collaborative filtering systems, while cosine similarity is commonly used in content-based recommendation systems. Pearson correlation can be used in both collaborative filtering and content-based recommendation systems. It is also common to use a combination of similarity metrics to improve the quality and accuracy of recommendations.
