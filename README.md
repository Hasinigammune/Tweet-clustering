# Tweet-clustering

Dataset used: ''foxnewshealth.txt'' 
dataset (https://archive.ics.uci.edu/dataset/438/health+news+in+twitter)
Dataset is stored in Google Drive and a url is given in the code.

##Preprocessing Data
We do the following steps
1. Seperate the tweet id and timestamp from the tweet(when reading data into a dataframe)
2. Remove any word that starts with the symbol @ e.g. @AnnaMedaris
3. Remove any hashtag symbols e.g. convert #depression to depression
4. Remove any URL
5. Convert every word to lowercase

##Clustering
We test k-means clustering for several k values
We plot the Graph of SSE vs number of clusters for visualization
