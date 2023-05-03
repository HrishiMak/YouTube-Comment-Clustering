# YouTube-Comment-Clustering
## Synopsis:
Performed classfification of the comments on the videos of four YouTubers - Cleo Abram, Physics Girl, Jet Lag: The Game, Neo into spam and non-spam using K-means clustering.
## Pipeline of the Model:
### *Data Pre-processing:*  
Analysing the dataset for any NaN values which are removed by dropping them from the dataset. Dataset is shuffled. Cleaning the data using NLTK library and training a Word2Vec model from gensim library. Vectorising the comments.     
### *Creating a new dataset:*  
Performed PCA on the sparse matrix of vectorised comments created to reduce them to 1-dimension. Using the vectorised comments as a new column, performing Label Encoding on the feature columns - "User" , "Video_Title", "Comment (Author)" -> A new dataset is generated to be used for clustering.   
### *K-means Clustering*   
### *Visualising the clusters*  
### *Hierarchical clustering on a set of 1000 points from the dataset*  
