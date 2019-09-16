# Web-scraping-and-clustering-reddit

# Overview
In this project I explore some of the characteristics that determine the score and the number of comments of a reddit. Specifically, I study a dataset with 1000 records of the top reddits for  the 'askscience' subreddit. In order to do that, I use Python Reddit API Wrapper (PRAW)  to get the data from reddit web site. Initially, I obtain attributes such as, author, title, score, id, url, comms_num, created and body. Then, by using the author column, I extract the comment_karma and  link_karma. These web scraping task are in the file reddit_scraping.ipynb.

In another notebook(reddit_data_analysis. ipynb), I analyze the distribution of reddits with respect to the numerical variables of my dataset. I investigate the correlation among different features of the data. Using centroid base clustering methods such as kmeans, AgglomerativeClustering and others, I obtain that this data has a structure formed by two clusters. Additionally, the same conclusion is obtained using density based methods like DBSCAN. Finally, I show most used words in each cluster.

 
 # Bibliography
 
  1. [Python Reddit API Wrapper(PRAW) documentation](https://praw.readthedocs.io/en/latest/)
  
  2. [silhouette method in scikit-learn](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)
