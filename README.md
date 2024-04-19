# Mushroom Data Analysis

## Introduction

The objective of this project is to practice data analysis and possibly learn about machine learning. The reason I chose the dataset about mushrooms for this project was because I was able to ask specific questions about the dataset, and I was curious to find patterns having to do with the characteristics of the mushrooms. In particular, I was interested to find which features have a connection with whether or not a mushroom is poisonous. 

I had one hypothesis which is that I think poisonous mushrooms will be more likely to have a strong and/or unpleasant scent, and this can be tested since odor is one of the attributes in the dataset. The 3 questions I asked about the data are listed below:
1. Are there certain odors that are more common with edible or poisonous mushrooms?
2. Which type of habitat had the most edible mushrooms? 
3. Are there mushrooms that have similar or the same features, and among these are there some that are edible while others aren’t? In other words, are there poisonous mushrooms that can be mistaken for edible ones based on the data?

## Selection of Data

The dataset has about 8,000 rows, each row representing a mushroom sample with 23 attributes. According to the description on Kaggle, the samples are only hypothetical. However, the samples correspond to real mushroom species in the guide book “The Audubon Society Field Guide to North American Mushrooms (1981).” The dataset was contributed to the UCI’s (University of Irvine, California) machine learning repository.

## Methods
Tools:
- Numpy, Pandas and Matplotlib for data analysis

## Results

For the first question, (which odors are more common with edible or poisonous mushrooms) the majority of the edible mushrooms were odorless, with a few smelling like almonds or anise. The poisonous mushrooms, on the other hand, had a variety of odors and none of them were odorless. The most common scent of the poisonous mushrooms was a foul smell. My hypothesis that the poisonous mushrooms are more likely to smell unpleasant and stronger compared to the edible ones turned out to be correct. 

For the next question, I asked which habitat has the highest amount of edible mushrooms. In other words, if someone wanted to forage for mushrooms, where would be the best place to find them? The result was that the woods had the most edible mushrooms, with grasslands as a close second. However, in both of these places there are many poisonous mushrooms as well.

## Discussion 

For the first question, since there is very little similarity in the odor values between the edible and poisonous mushrooms, this attribute can be considered a strong predictor of the edibility of a mushroom. However, risk is important with this topic; no one should assume a mushroom is safe to eat based on the scent (or lack thereof) alone.

On the other hand, the habitat that the mushroom is found in does not have much of a relationship with the edibility of the mushroom. In all habitats, there was a significant amount of both edible and poisonous mushrooms. Anyone foraging would need to closely inspect the mushrooms to check if they're safe, regardless of where they were found.

To summarize, this data is helpful because it's important to identify which attributes have a stronger relationship with the edibility of the mushrooms so that you or a machine learning model can make more accurate predictions.
