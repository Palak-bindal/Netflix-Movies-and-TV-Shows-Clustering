# Netflix_Movies_and_TV_Shows_Clustering
![image](https://github.com/vks2268/Netflix_Movies_and_TV_Shows_Clustering/assets/117895012/e9aeb912-4707-4cec-9665-9c1ccee94118)

# Introduction

Introduction Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

# Problem Statement

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this information with additional external datasets such as IMDB ratings and rotten tomatoes can yield a plethora of fascinating results.

# Project Summary

● In this project, we tackled a text clustering problem where we had to classify/group Netflix episodes and movies into specific clusters so that the shows and Clusters within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

● Netflix was found to host more films than TV series on its platform, and the overall number of shows added to Netflix is increasing exponentially. Additionally, the majority of Netflix's shows were produced in the United States and targeted towards adults and young adults.

● The director, cast, country, genre, and description were chosen as the attributes to cluster the data based on. The TFIDF vectorizer was used to tokenize, pre-process, and then vectorize the values in these properties.

● Through TF-IDF Vectorization, we created a total of 10000 attributes.

● We used Principal Component Analysis (PCA) to handle the curse of dimensionality. 4000 components were able to capture more than around 90% of the variance, and hence, the number of components was restricted to 4000.

● The ideal number of clusters, with a decent WCSS value, was found to be 9 when we initially constructed clusters using the k-means clustering algorithm. The elbow method and Silhouette score analysis were used to get this result.

● Built a recommender system based on cosine similarity and cosine distance that  suggest 10 movies based on the movie given as input.
