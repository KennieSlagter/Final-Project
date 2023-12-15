# Final-Project
=======
# The "dan/als" mistake in Twitter posts

## Abstract 
This project is about frequency the "dan/als" mistake in Dutch posts from Twitter between the different ages. We will be looking both at the "dan" mistake as the "als" mistake. This will be done using a dataset of Dutch Twitter posts and filtering out the posts with the "dan/als" mistake and filtering out the user's age and putting these statistics in a graph. (still need to add the results in short and the conclusion)

## Background information
Still need to research this.

## Research question and hypotheses
I am currently studying Information Science and working on the topic of variations in language. I want to find out the frequency of the "dan/als" mistake and look both at the "dan" mistake as the "als" mistake in social media posts of Twitter and to investigate whether there are any significant differences in the occurrence of this error across various age groups. I want to help readers understand when to use "dan" and "als" correctly. We should adhere to Dutch language standards. Nowadays, younger people in the Netherlands are struggling with the Dutch language. On social media, they tend to use a lot of abbreviations and often omit punctuation. This trend is not conducive to improving their Dutch language skills.

I believe that most people online use "dan" and "als" correctly, but I think younger individuals tend to make the "dan/als" mistake more frequently.

## Method
The method I will be using. I will be using a large dataset of Dutch Twitter posts from https://huggingface.co/datasets/dutch_social. Which is a dataset that contains 271,342 tweets, where all the tweets are in the Dutch language. I will be filtering out tweets based on the most common degrees of comparison in Dutch which are: 
| goed | beter | best |
| ---- | ----- | ---- | 
| graag | liever | liefst |
| veel | meer | meest |
| weinig | minder | minst |

I will filter the tweets with the following "dan/als" mistakes:
* beter als 
* liever als 
* meer als 
* minder als
* net zo goed dan
* net zo graag dan
* net zo veel dan
* net zo weinig dan

And measuring the frequency of the "als" mistake and the "dan" mistake separately and measuring the frequency of those mistakes between the following age groups:
* 13 - 20 Years
* 21 - 35 Years
* 36 - 60 Years
* 60+ Years

I will be getting the ages of the different users using the methods of Pandya, Abhinay, Mourad Oussalah, Paola Monachesi, and Panos Kostakos. They used amodel based on a Convolutional Neural Network to identify the age of each user. Which is better than the previous one that is made and is 12,3% more accurate to identify the ages of users on the Dutch dataset.[^1]

## References
[^1]: Pandya, Abhinay, Mourad Oussalah, Paola Monachesi, and Panos Kostakos. “On the Use of Distributed Semantics of Tweet Metadata for User Age Prediction.” Future Generation Computer Systems 102 (2020): 437–52. https://doi.org/10.1016/j.future.2019.08.018. 
        