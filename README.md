# #METOO: : a Spatio-Temporal, Social, Political, and Gender Based Analysis using its Propagation on Twitter

# Abstract

The #MeToo movement is a global movement against sexual abuse. It spread virally in October 2017 as a hashtag used on social media in order to show the widespread phenomenon of sexual harassment, particularly in the workplace. The idea is to fearlessly talk about any sexual abuse one might experience and to rebel against the culture of staying silent after going through such traumatising experiences. A lot of celebrities participated in this movement by highlighting their stories on social media, including renowned actress, personalities, and politics, but also persons from simple backgrounds. As a team we are motivated to understand the movement because of its intensity and controverse. It is a challenge to put aside our personal opinion as individuals and consider only the data around this thematic to arrive to an interesting yet objective datastory. 

# Research Questions

From most factual and clean to more interpreting and subjective Data Handling: 

- Which hashtags and users were the more associated to #metoo ? Who are the main influencers and targets ? (@)

- Did this mobilization rely more on tweets (personal stories), or on reply/retweets (sharing to show support) ?

- How did it start, how did it spread in time and in space ? Can we clearly identify the origin of the movement ? Why is this happening in 2017 ? Are there key moments ? Can we correlate activity peaks with public events (accused star, public affairs, etc.) ? How global is it ? How did people from different countries react (cultural aspect) ?

- How did the public opinion react ? Which were the main hot topics discussed ? (sentiment analysis, natural language processing, lexical fields)

- What was the role of men within this movement ? Can we associate #metoo movement with a gender debate ? 

- Is it more a popular or a political movement ? How much is it a backlash against Trump administration ?

Trying to use the above questions to answer more precise and controversial questions: 

- Group effect, cathartic experience, collecting together, showing the example... How did technology and social media give women a voice and a sense of bravery in calling out ? Did it spun out of control ? Is there a danger of witch-hunt effect ? Could a similar movement have happened without social media ? And if yes, how ?


# Datasets

**OPTION 1**
Ideally use: 

[MeToo.sqlite](https://data.world/from81/390k-metoo-tweets-cleaned?fbclid=IwAR0JG4UvQurBZGPD7hWQzOOXZ_EAEL2EwiMYR4kLleQMjSPYtdaj4QgsuIY) :

Which has the following features:
-name of twitter user
-number of followers
-written content of tweet
-number of retweets
-language
-country
-city or state
-creation date

Number of Tweets: 390 000 tweets. 

**OPTION 2**
Else : 
[metootweets.csv](https://data.world/rdeeds/350k-metoo-tweets)

Which has the following features:
-name of twitter user
-number of followers
-written content of tweet
-creation date

Number of Tweets: 350 000 tweets. 

& Combined with an API request to get additional information for the referenced Twitter users. (localisation and gender information)


# Internal milestones till milestone 2

1. Find how to process an sqlite file format to be able to use an interesting data set AND/OR make an API request using Twitter user ID. 

2. Extract the raw data such as:
- the hashtags (#) used, 
- @ references, 
- number of followers, 
- gender, 
- geolocalisation, 
- retweets or reply, 
- timestamps of the tweets,
- negative or positive language in the tweets,
- key words for in depth analysis (for example: “Trump”)

3. Process this data into usable structures and evaluate if their output is pertinent for the subsequent data story. 


# TA Questions

- Can we try to webscrap for information about the Twitter users (notably geographic info) using Twitter API? 
in other words: How do we get geolocalisation and gender info from Twitter using just a user ID? 

- How do you process an sqlite data format? 

- How can we define useful keywords for data processing steps such as sentimental analysis (which words are pejorative or positive) or how to extract keywords related to gender, age, fame, profession etc…? 



