# Carpe Diem Ski Lab
Hackathon project for Technica 2021

![Jackson.jpeg](Jackson.jpeg)




## Introduction

We are aiming to help introduce people to new ski trip buddies that share their core values.

By creating a match-process that uses data science to extrapolate people's values based on how they speak about their lives and themselves, we can:

Connect people with new friends who share their specific motivations for going skiing/snowboarding, as well as in life, who they are likely to enjoy a ski trip with
Create foundation for more comprehensive friendship-algorithm
Improve tourism + accessibility for adult beginners at ski resorts 


## Methodology
Analyze past text-data written on OkCupid, a popular dating site 

### The dataset
We used the OkCupid Profiles dataset from Kaggle, which contain multiple short essays written on several different topics from each user. These are a variety of topics that revolve around a user's interests, values, dreams and daily life, as well as the type of people they are seeking to associate with.


You can view the original dataset here: https://drive.google.com/drive/folders/1uO-uTPUltX8vru-a-Jt-0hufTME8s1YN?usp=sharing

## The Hack

Given the 24 hour time constraint of the hackathon, we decided to focus on declaring 3 popular reasons or value drivers, for why people would go skiing/snowboarding: for fitness, personal growth, and interpersonal connections. Many utilize all 3 as values, however for simplicity we focused on separating out into 3 groups - each group contains all of the users that hold that item as a value. These groups are therefore not mutually exclusive.

We then filtered for common mutual information scores, or sets of two words that are most likely to occur together, for each set of users that hold a given value. 

We used this to find patterns in the bigger picture for common vocabulary or speech patterns per value.

We then used the differences in these patterns across the 3 values, fitness, personal growth and interpersonal, in order to come up with some better questions for Ski Lab users to answer, than those of the original dataset, that still achieve the mission of getting to know each person on a level deeper than the surface. We used design thinking and focus group principles in order to extract purpose behind the questions to tease out the larger pattern differences in vocabulary and speech patterns across the 3 value groups.

We then created a simple data collection survey via Typeform to ask our improved questions, and created a landing page for people to learn more about our mission of connecting people with new ski buddies who share similar motivations/values for getting out on the slopes. 

People are now able to fill out this Typeform to answer questions that were built with our data science-informed principles in mind. Currently we will be performing simple searches manually to cross-reference their essays answering our questions, in order to determine which value of the 3, that they value the most. Based on this, we can manually email users with their curated introductions to friends who share the same value motivation behind going on ski trips.

In the future, given more time we will be able to build out a robust model and automate sending out email or text introductions to friends who are recommended for one another.


