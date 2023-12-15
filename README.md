# Final-Project
=======
# Method
The method I will be be using. I will be using a large dataset of Dutch twitter posts from https://huggingface.co/datasets/dutch_social. Which is a dataset that contains 271,342 tweet, where all the tweets are in the Dutch language. I will be filtering out tweets based on the most common degrees of comparison in Dutch which are: 
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
I will be getting the ages of the different users using the method of Pandya, Abhinay, Mourad Oussalah, Paola Monachesi, and Panos Kostakos. Where they used model based on Convolutional Neural Network to identify the ages of each user.[^1]

## References
[^1]: Pandya, Abhinay, and Mourad Oussalah, and Paola Monachesi, and Panos Kostakos. 2020. On the use of distributed semantics of tweet metadata for user age prediction. Future Generation Computer Sytems, 102, 0167-739X: 437-452. https://doi.org/10.1016/j.future.2019.08.018  
        