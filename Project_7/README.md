### Wrangle and Analyze Data

My goal is wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.
Data wrangling which consists of:
1.	Gathering data from 
(i)	The WeRateDogs Twitter archive;
(ii)	The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network;
(iii)	Each tweet's retweet count and favorite ("like") count at minimum, and any additional data I find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. 

2.	Assessing data
(i)	After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues.
3.	Cleaning data


