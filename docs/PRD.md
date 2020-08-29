## The basics
1. Collect username and password from user, store it safely
2. Login to twitter and collect the tweets from timeline
3. Bucket the tweets based ont he given day say 1/1/2020, 1/2/2020
4. Note: In free edition of twitter APIs, twitter limits the amount of queries and tweets we can get from our timeline. 
5. Process the response data from twitter and store them in a database. Preferable MongoDB
## Data sorting
1. In each tweet, count the occurance of all words and maintain it as one of the key to the given tweet
2. When analytics is initiated

    a. simply count the occurance of each word from all the tweets on a given day

    b. sort them by maximum occurance

    c. Ensure to exclude the not useful words to analyze the trend like prepositions, symbols (,.!@ etc.,)

    d. Create the ability to query and filter the tweets from the stored DB based on the given keyword
## Data visualization
1. Similar to twitter trend, provide trend of top 10 or 20 words from the user timeline
2. Create a simple visualization of all the top words from the analyzed day of visualization similar to the below picture (word cloud or word collage)

https://www.dreamstime.com/abstract-word-collage-background-covid-word-cloud-concept-illustration-beautiful-text-art-wallpaper-covid-purple-word-cloud-purple-image175825309

3. For the selected word, project the corresponding tweets as per the user desire

## App frontend
<TBD>
