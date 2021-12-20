# Project_Social-InformationNetworks

Social media data from Twitter, Instagram, Facebook, etc. can be analysed using various social analysis models and techniques to gain insights and recommendations. The main aim of the project is to use Python and NetworkX to analyse Twitter communities and followers using social network analysis techniques and also provide recommendations for new followers on Twitter based on the Network Analysis.

The scraping of Twitter data is done using the Twitter API and processed to get analysis graphs using NetworkX and iGraph libraries. The 3 community detection algorithms are compared - Leading Eigen Vector, Multilevel and Label Propagation in terms of modularity, membership and iGraph plots is also completed. Also, the recommendations were done by analysing the scraped Twitter data using NetworkX and generating a friendship graph to identify new people to follow.

The data for the project is obtained by scraping real time user Twitter data using Tweepy and Twitter API. Use of the Twitter API is obtained by creating a twitter developer account and obtaining the authorization keys and secret keys (4 in total) for connecting and using the API. Crawling the data is a long process, and for a small user account it took exactly 2d 22h 43min 17s. Crawled data saved as a pickle file and can be used for analysis directly.

TECH STACK:

* Python
* Tweepy / Twitter API
* NetworkX
* iGraph
* Community Detection Algorithms
  * Leading Eigen Vector Algorithm
  * Multilevel Algorithm
  * Label Propagation Algorithm 
