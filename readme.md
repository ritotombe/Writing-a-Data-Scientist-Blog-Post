### Brief
This work is an extension of my own work for another ND (Data Analyst Nanodegree) for this ND (Data Scientist Nanodegree).
I have raised a request to Udacity support to check whether this allowed and they permitted it. 

The project was to Gather, Assess, Clean and Analyse data from Twitter.

There are three data sources in the project:

1. twitter-archive-enhanced.csv: a file provided by Udacity contains most of the data
2. image_prediction.tsv: a file that should be downloaded programmatically using `requests` library
3. tweet_json.txt: data that gathered from Twitter API using `Tweepy` library

I am only using using two of them (1 & 3) in this project as it will be used for the analysis in the last section.

### Structure
The project structured as following:

- Gathering Data
    - twitter-archive-enhanced.csv
    - tweet_json.txt
- Assesing Data
    - Visual assessment
    - Programmatic assessment
- Cleaning Data
    - Quality Issues
    - Tidiness Issues
- Storing Data
- Analysing Data
    - Q1: What is the top rating?
    - Q2: Which correlate well to which column? (Rating, retweet, favorite)
    - Q3: What is the most favourited dog stage?
    - Q4: Can we predict number of favorites received?