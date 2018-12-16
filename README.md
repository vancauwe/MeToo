# The #MeToo movement and its propagation on Twitter : a Temporal, Gender Based and Sentimental Analysis

Please visit the resulting data story webiste at https://art345.github.io/

# Abstract

The #MeToo movement is a global movement against sexual abuse. It spread virally in October 2017 as a hashtag used on social media in order to show the widespread phenomenon of sexual harassment, particularly in the workplace. The idea is to fearlessly talk about any sexual abuse one might experience and to rebel against the culture of staying silent after going through such traumatising experiences. A lot of celebrities participated in this movement by highlighting their stories on social media, including renowned actress, personalities, and politics, but also persons from simple backgrounds. As a team we are motivated to understand the movement because of its intensity and controverse. It is a challenge to put aside our personal opinion as individuals and consider only the data around this thematic to arrive to an interesting yet objective datastory. 

# Research Questions

From most factual and clean to more interpreting and subjective data handling: 

- **Temporal Analysis** : 
How did it start, how did it spread in time ? Can we clearly identify the origin of the movement ? Are there key moments ? Can we correlate activity peaks with public events (accused star, public affairs, etc.) ? 

- **Sentimental Analysis** (results extracted into features_per_tweet.csv) :
How did the public opinion react ? Which were the main hot topics discussed ? (sentiment analysis, natural language processing, lexical fields)

- **Gender Analysis** (results extracted into genderData.csv) :
What was the role of men within this movement ? Can we associate #metoo movement with a gender debate ?

Open-ended data interpretation question: 

- Group effect, cathartic experience, collecting together, showing the example... How did technology and social media give women a voice and a sense of bravery in calling out ? Did it spun out of control ? Is there a danger of witch-hunt effect ? Could a similar movement have happened without social media ?

# Datasets

[metootweets.csv](https://data.world/rdeeds/350k-metoo-tweets), raw CSV database, Ryan Deed.

Which has the following features:
- name of twitter user
- number of followers
- written content of tweet
- creation date

Period : between October 2017 and February 2018.
Number of Tweets: about 380 000 tweets. 


# Internal milestones

Achieved : 

- Temporal data exploration
- Sentimental data extraction using LIWC
- Gender data extraction using genderperform
- Interactive timeline figure, including major events
- Shaped wordcloud
- LDA topic clustering
- Sentimental Analysis Exploration 
- Bivariate Gender-based and Sentimental Analysis 
- Bivariate Temporal and Sentimental Analysis
- Bivariate Temporal and Gender-based Analysis
- Data Story construction and presentation

# Contribution of group members

All the three members will contribute to the final presentation (poster creation and oral preparation).

**Laure** : gender data extraction using genderperform, sentimental data using LIWC extraction and application, plotly figures (overall sentimental & bivariate sentimental (gender, time) analysis), textual analysis.

**Caroline** : gender data extraction using genderperform, date and context research about the movement for the timeline, data story design and formatting using jekyll, textual analysis.

**Arthur** : raw data exploration and analysis, word cloud coding, interactive hashtag evolution timeline, LDA topic clustering (coding and displaying), textual analysis.


# Final Data Story

Please find our final product, our data story, here : https://art345.github.io/

**Note** : for more details about how the data story using beautiful_jekyll was constructed and created, we invite you to go to the git of origin: https://github.com/art345/art345.github.io
