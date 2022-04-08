# FLASH-BERT

FactCheck and FactCheck2 are two new tiny datasets proposed in the paper.
The FactCheck dataset provides two sets of news instances: one with 100 real news samples and another with 100 fake news samples. Actual news stories were gathered from official Twitter accounts of well-known news media outlets such as Times Now, India Today, Mirror Now, and others. 'Link', 'Source', 'Tweet', 'Category', and 'Label' are the five columns in the set of genuine news. The 'Link' field contains the appropriate Twitter link for that tweet, the 'Source' field contains the name of the media firm whose Twitter handle the tweet was retrieved from, the 'Tweet' field contains the tweet itself, and the 'Category' field contains the news domain. The real news stories are divided into three categories: 33 are linked to 'Crime,' 33 are related to 'Health,' and the remaining 34 are related to 'Politics.' Finally, all real instances have a 'Label' of '0,' indicating that this is a genuine news instance. The India Today Fact Check website was used to gather the examples of fake news. The fake news collection has four columns: 'Link,' which contains the article's URL, 'Claim' which has the actual text, 'Explanation' which explains why the claim is wrong, and 'Label' which has three values: Half true, Mostly lies, and Absolutely false. The dataset was transformed to include just two attributes - the 'text' and the 'label' which takes the value of '0' for all real news occurrences and '1' for all fake news instances, because the goal of this work is to categorize fake and real news alone.

The FactCheck2 dataset is merely a supplement to the FactCheck dataset, with the sole difference being the amount of instances of actual and fraudulent news. It includes 600 examples of legitimate news and 120 examples of fraudulent news. It's essentially an imbalanced class dataset, similar to what you'd find in real life. The rest of the information is identical to that provided by FactCheck.

| Dataset | #Real instances | #Fake instances | Total instances |
| :-: | :-: | :-: | :-: |
| FactCheck | 100 | 100 | 200 |
| FactCheck2 | 600 | 120 | 720 |
