<div>
  <img src="https://github.com/janhenner/TwitterDataWrangling/blob/master/img/TwitterDataWrangling.png?raw=true" alt="Disaster Response Project" width="700"/><br>
</div>

# Insights on Twitter Tweets from WeRateDogs

## General info
Our focus in this project is __producing a high-quality dataset__. We __wrangle the data__ to enable further analysis. We rigorously assess and clean: we check missing data/completeness, tidiness, and data specific cleaning needs. Each cleaning activity follows a three-step __approach to define, code, and test__.

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

We collect the tweets and metadata using the __Twitter API__ _Tweepy_. We combine the tweets with a classification of a dogs breed. The classification is based on a neural network and is downloaded at code runtime. Additional information about the tweets is obtained from a file downloaded to the file system.

## Requirements
Python 3 mainly with the packages Pandas, requests, json and tweepy, i.e. the Twitter API.

## Instructions
To run `wrangle_code.ipynb` a Twitter account is needed to get the API input _consumer_key, access_token, consumer_secret, and access_secret_. The content of data is expected in the same folder as the Python notebook.

## Files
Folder `notebooks` contains Jupyter notebooks used for wrangling and report creation.

`wrangling_code.html` is an HTML version of the executed `wrangle_code.ipynb`. `report_wrangle.html` is a 500-word report about the data wrangling performed. `report_external.html` is a 500-word report for a general audience.

`data` contains the neural network predictions, an additional input file and the `wrangle_code.ipynb` output `tweet_json.txt` from the gather data step.
