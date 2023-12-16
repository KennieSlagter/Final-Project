# Final-Project
=======
# The "dan/als" mistake in Twitter posts

## Abstract 
This research project is about frequency the "dan/als" mistake in Dutch posts from Twitter between the different ages. I will be looking both at the "dan" mistake as the "als" mistake. This will be done using a dataset of Dutch Twitter posts and filtering out the posts with the "dan/als" mistake and filtering out the user's age and putting these statistics in a graph. (still need to add the results in short and the conclusion)

## Background information
On this specific topic, there was not any research done, but there is research done on the use of grammar and the correctness of grammar on social media, especially with verbs. The article of Bernts (2022) [^1] is about the frequency of grammar mistakes and their topic was specifically on verbs that sound the same, but are different in which tense they are used and looks at the frequency of the mistake with verbs that end with "t", "d" or "dt". Those are words like "word/wordt", "gebeurt/gebeurd" en "rusten/rustten". They did this by looking at corpora from WhatsApp and Facebook, looking specifically at younger people. This article found that if the verb is d-dominant, there was a low frequency of mistakes, but if the word was t-dominant or dt-dominant, the frequency of mistakes was much higher.

The second article by Verheijen, Spooren, and van Kemenade (2020) [^3] looked at the Dutch youth and their usage of computer-mediated language (CMC), and how well they do in school writing. They tested this by making 400 participants, all having different education levels write an essay and fill in a questionnaire about their CMC use. They found out that most participants can differentiate between the CMC language and the standard Dutch well. They found out that using CMC language on social media does not correlate to a worse formal Dutch language.

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

I will be getting the ages of the different users using the methods of Pandya, Abhinay, Mourad Oussalah, Paola Monachesi, and Panos Kostakos[^2]. They used a model based on a Convolutional Neural Network to identify the age of each user. Which is better than the previous one that is made and is 12,3% more accurate to identify the ages of users on the Dutch dataset.

## References
[^1]: Bernts, Marjolein. Het effect van frequentie en homofonie Op Spelfouten in Werkwoorden op sociale media, April 29, 2022. https://theses.ubn.ru.nl/server/api/core/bitstreams/bc4a3606-ae9c-44da-9859-490cb9127df4/content. 
[^2]: Pandya, Abhinay, Mourad Oussalah, Paola Monachesi, and Panos Kostakos. “On the Use of Distributed Semantics of Tweet Metadata for User Age Prediction.” Future Generation Computer Systems 102 (2020): 437–52. https://doi.org/10.1016/j.future.2019.08.018. 
[^3]: Verheijen, Lieke, Wilbert Spooren, and Ans van Kemenade. “Relationships between Dutch Youths’ Social Media Use and School Writing.” Computers and Composition 56 (May 15, 2020): 102574. https://doi.org/10.1016/j.compcom.2020.102574.
        