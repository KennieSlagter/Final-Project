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

## References
[^1]: 
        