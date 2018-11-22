# prj_wrangle_and_analyze_data

* Gathered data from the archive tweets from [WeRateDogs](https://twitter.com/dog_rates) and other web resources including twitter API.
* Assessed and cleaned datasets.
* Performed analysis and provided the visualization of the results: which dog breeds and dog stages are most popular in terms of the retweet numbers, favorite numbers and the numbers of occurrences in tweets.

## Quick Start
1. Clone this project to your local.
2. Create a file named tweet_key.json, open it with text editor and put you twitter keys in it with below format:  

`{`  
	`"consumer_key" : "YOUR_CONSUMER_KEY",`  
	`"consumer_secret" : "YOUR_CONSUMER_SECRET",`  
	`"access_token" : "YOUR_TOKEN",`  
	`"access_token_secret" : "YOUR_TOKEN_SECRET"`  
`}`  

3. In the project's directory, create a folder called other, and put above tweet_key.json file in the folder.

## Notes
In the wrangle_act.ipynb file, in order to skip the twitter API calls to download data, `if 1==0:` is added. If you want to download the data by yourself, please find it and remove `if 1==0:` before the method calls.
