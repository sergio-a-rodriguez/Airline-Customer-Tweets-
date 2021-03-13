MGTA 415
Professor Shang
Team Members: Anushka Joshi, Jacob Killingsworth, Sergio Rodriguez

Airline Industry Sentiment Analysis

Abstract

Twitter contains massive amounts of information regarding airline services and customer satisfaction. This report analyzes the sentiments around customer Tweet data to find the best and worst airlines in customer preference and service and also the demographics and regions of customers writing reviews. It also looks at the most common reasons why customers are facing issues. Models to predict sentiments of Tweets were also built and visualized using 

We have data from 2015 Airline customer tweets detailing their experiences. Sentiment with our data from 2015 Airline customer tweets is fairly recent and relevant. However, due to this last year dealing with covid, many of the circumstances that come with traveling in the US have changed. In particular due to the pandemic, space and social distancing have been the most frequent advice given by the Center for Disease Control & Prevention as well as the World Health Organization.At the beginning of 2021 covid-19 vaccines have begun to roll out in regions across the country and we can expect the market for travel will see an increase in demand during the timeline for vaccine rollots which is coinciding with restrictions being lifted across the country. States like Texas , Florida, and Georgia have reopened all activities in the state to some capacity even if limited. Others have launched preemptive marketing efforts to prepare its citizens with guides for reopening their respective region. We want to see if we can find any relevant adjustments that airlines can make to be better suited to service customers as the market for travel begins to ramp up towards its normal volume through the summer of 2021.  The timeline for vaccines presented by gov officials is to have enough of the US population vaccinated by June 2021 to effectively end the pandemic.

Airplanes are not very conducive for enabling the suggested 6ft distance between individuals due to current airplane designs which have row seating clustered together usually in groups of 3. We can expect to see some adjustments in the design of the seating to accommodate safety measures due to the pandemic. The market has observed a decrease in overall travel throughout the United States since the epidemic started in 2020. This was expected as many stay-at-home mandates were put into effect in counties across the country. These mandates effectively restricted all travel to only essential travel and minimizing/eliminating leisure as well as international travel. 
To accommodate for safety precautions suggested by the CDC and WHO  the airlines could place a cap on the number of tickets they will sell per flight. This decrease in the number of serviced passengers per flight could help limit the risk of exposure to covid-19 virus. For example, airlines with rows seating 3 people each will have to either redesign or temporarily restrict usage of the middle seats during flights. These adjustments are results of the response to the pandemic. 


BACKGROUND

The airline industry is a huge economic force in terms of its operations in every corner of the globe as well as its impact on other industries. In the US airline industry, approximately 100 certificated passenger airlines operate over 11 million flight departures per year, and carry over one-third of the world’s total air traffic. US airlines reported over $160 billion in total revenues, with approximately 545,000 employees and over 8,000 aircraft operating 31,000 flights per day (ATA 2007). With such high volumes of customers involved and so much money flowing in and out, it is in every airlines’ best interest to look at customer satisfaction to improve productivity and maximize profits. 

Where better to turn than to social media where travellers express their opinions and reviews on Twitter. It seems customers tend to complain first to service providers with the hopes of a quick fix and immediate better service, and then their frustrations turn to social media where they write reviews for the public to see.

In this report we aim to analyze and understand passenger sentiments for the US airline industry based on a Twitter dataset from 2015 taken from Crowdflower's Data for Everyone library.  

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service"). The dataset includes a column labelled “sentiment_confidence” which is indicative of the proportion of contributors which chose to identify that label with the individual tweet out of all contributors. The sentiment linked to each individual tweet is the label [‘positive’, ‘neutral’,’negative’] which represented the highest “sentiment_confidence”. 

Some of the questions we aim to answer are as follows: What are the best and worst airlines and what are the most common problems encountered by customers? Can the sentiment be predicted using Logistic Regression and text classifiers?

There are a few hypotheses being tested in this report based on sociological assumptions. One is that the longer tweets will have more of a negative sentiment because people generally tend to rant more if they have more negative things to say. Secondly, when looking at tweets by region, passengers from the Northeast region will have more negative sentiment tweets because of the stereotype of east coasters being less patient. Similarly the passengers from the South and Midwest regions will have more positive sentiment to their tweets. Lastly because of its reputation, it is also hypothesized that Southwest Airlines will have more positive sentiment tweets referring to them than the other airlines.
Some descriptive analysis is done preliminarily before modelling an Ingram Language model, Word-2-vec and TF-IDF model. Sentiments were predicted for all the tweets using these models also with the help of weakly supervised text classification.

METHODOLOGY

To begin with, we did some descriptive analysis. Firstly we found that the data was imbalanced as it has a lot more negative sentiment. This makes sense as people remember negative events more and generally have more to say or rant about in social media. Among negative sentiments, United Airlines was the top; they have the greatest ratio of negative sentiments to total sentiments with US airways and American Airlines close behind. The largest reasons behind the negative reviews for most of the airlines was because the passengers were not satisfied with customer service. For Delta the top reason for negative review was because of delayed flights. The reason that is least talked about in the negative reviews for all airlines is damaged luggage and long lines. 

RESULTS 
Customer Service was the most commonly seen negative reason given by customers of the airlines. During the pandemic, the customer service aspect of travelling evolved from simply checking in on the customers experience to protecting customers from a deadly virus. Many instances during travelinng


Discussions
Define your own research problem and justify its importance
How high accuracy on classifying sentiment in Twitter messages?


Citations

Air Transport Association of America (ATA), 2007 Economic Report, www.airlines.org.
