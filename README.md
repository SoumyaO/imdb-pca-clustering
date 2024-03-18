# Unsupervised Learning - Clustering
[Code](https://github.com/SoumyaO/imdb-pca-clustering/tree/main/code) | [Data](https://github.com/SoumyaO/imdb-pca-clustering/tree/main/data) | [Report](https://github.com/SoumyaO/imdb-pca-clustering/blob/main/Report_Group%208_Group%20CW%202.pdf)

### Contributors
[Soumya Ogoti](https://github.com/SoumyaO)  
[Linh Nguyen](https://github.com/jill-data)  
[Wenxu Tian](https://github.com/Wayne599)  
[Hang Su](https://github.com/Hangbiob)  
[Fan Xia](https://github.com/FanXia1227)

## Description
This project involved applying unsupervised learning techniques for clustering movies from the IMDB dataset. The python libraries Sklearn, Pandas, Matplotlib and Seaborn were used for this analysis. The interplay between run time of movies, the number of votes and ratings and its effect on the revenue that the movie generated was investigated.

Data pre=processing involved handling missing values and standardising numerical features.
Prinicpal component analysis (PCA) was performed on the dataset to identify the components that account for the most variance in the data. In order to determine how strongly each feature influences the principal components, biplots were used.

The data was clustered using k-means and heiracrical clustering. For k-means clustering elbow method was used to get a rough estimate of k (=3). However, with this value, the cluster boundaries were not well defined. To address this sihouette analysis was done which resulted in k=2. This resulted in better defined clusters. It can be seen that movies with shorter runtimes, lower ratings and votes, and lesser revenue form a cluster. This findings indicate that shorter movies with less popularity generate less revenue.

Another approach for clustering, Heirarchical clustering was employed as it allows better visialisation of clusters, customisation of linkage and the number of clusters need not be pre-defined. Multiple linkage strategies - average, complete, centroid and single linkage were investigated. Looking at the dendrograms, the number of clusters was determined to be 3. A surprising finding of this analys was that the cluster that generated the highest revenue contained movies with above-average running times and number of votes, but with lower than average ratings. 
