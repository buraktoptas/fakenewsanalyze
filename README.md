# fakenewsanalyze
The latest hot topic in the news is fake news and many are wondering what data scientists can do to detect it and stymie its viral spread. This dataset is only a first step in understanding and tackling this problem. It contains text and metadata scraped from 244 websites tagged as "bullshit" by the BS Detector Chrome Extension by Daniel Sieradski.

Warning: I did not modify the list of news sources from the BS Detector so as not to introduce my (useless) layer of bias; I'm not an authority on fake news. There may be sources whose inclusion you disagree with. It's up to you to decide how to work with the data and how you might contribute to "improving it". The labels of "bs" and "junksci", etc. do not constitute capital "t" Truth. If there are other sources you would like to include, start a discussion. If there are sources you believe should not be included, start a discussion or write a kernel analyzing the data. Or take the data and do something else productive with it. Kaggle's choice to host this dataset is not meant to express any particular political affiliation or intent.

Contents
The dataset contains text and metadata from 244 websites and represents 12,999 posts in total from the past 30 days. The data was pulled using the webhose.io API; because it's coming from their crawler, not all websites identified by the BS Detector are present in this dataset. Each website was labeled according to the BS Detector as documented here. Data sources that were missing a label were simply assigned a label of "bs". There are (ostensibly) no genuine, reliable, or trustworthy news sources represented in this dataset (so far), so don't trust anything you read.

Fake news in the news
For inspiration, I've included some (presumably non-fake) recent stories covering fake news in the news. This is a sensitive, nuanced topic and if there are other resources you'd like to see included here, please leave a suggestion. From defining fake, biased, and misleading news in the first place to deciding how to take action (a blacklist is not a good answer), there's a lot of information to consider beyond what can be neatly arranged in a CSV file.

How Fake News Spreads (NYT)

We Tracked Down A Fake-News Creator In The Suburbs. Here's What We Learned (NPR)

Does Facebook Generate Over Half of its Revenue from Fake News? (Forbes)

Fake News is Not the Only Problem (Points - Medium)

Washington Post Disgracefully Promotes a McCarthyite Blacklist From a New, Hidden, and Very Shady Group (The Intercept)

Improvements
If you have suggestions for improvements or would like to contribute, please let me know. The most obvious extensions are to include data from "real" news sites and to address the bias in the current list. I'd be happy to include any contributions in future versions of the dataset.

Acknowledgements
Thanks to Anthony for pointing me to Daniel Sieradski's BS Detector. Thank you to Daniel Nouri for encouraging me to add a disclaimer to the dataset's page.
