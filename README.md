# crypto_bot_trader
Automated python bot that trades crypto in real time


## Architecture




# First Step
## Develop Data ingestion pipeline

We will use a combination of crypto exchange APIs and popular social media apps such as telegram, twitter and reddit to develop a comprehensive training set. 

For the data lake (initial data storage) and data warehouse (processed data storage) we will use S3 buckets in AWS.

For feature engineering and model deployment we can use EC2 + sagemaker. 

To integrate the bot with the trading application we can use a flaskAPI to develop a model endpoint that can be pinged by the bot to make trades. 
