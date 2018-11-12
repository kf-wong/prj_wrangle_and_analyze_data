# prj_wrangle_and_analyze_data
This is the repositoty of 'Wangle and Analyze Data' project of Udacity.

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