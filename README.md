# BigDataAnalytics
Various concepts used in big data - mapreduce, spark implementations, etc. 

Task 1
Step 1: Remove the records where “user_verified” is “FALSE”. 
Step 2: For the remaining records (“user_verified” is “TRUE”), group by created date, and count the number of tweets for each date. 
Example: If “tweet_created_at” is “Tue Nov 01 01:57:25 +0000 2016”, the created date is “Nov 01”.
Step 3: For the date with highest number of tweets (you can figure it out from step 2), calculate the sum of “favorite_count” and “retweet_count” for each tweet on that day. Then report the text content (“text_”) of the top 100 tweets with highest sum. Count the word frequency of the 100 tweets and report the result (Note that data cleaning steps before wordcount can be done outside of Spark operations).

Task 2
You will use find_text.csv for this task. There are two columns in this document: “id_str” and “text”. The second column is empty. Please find out the text content of each tweet according to “id_str” joining Amazon_Responded_Oct05.csv and fill in the “text” column.

