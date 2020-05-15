# Starbucks Mobile Apps Offer
*Udacity Data Science Nanodegree Capstone Project*

### Project summary:

This project is a part of Udacity's Data Science Nanodegree, the capstone project - to encourage the students to leverage what we've learned throughout the program to build a data science project of our choice.
The project includes submissions of a blog post and a Github repository.

I chose the Starbucks Capstone Challenge because it closely related to my career as a marketer, whose main goals are but not limited to optimise ROI and improving customer experience.

The notebook in this repo includes details of my analysis, with below structure:
1. Perform Exploratory Data Analysis (EDA), clean & transform the dataset
2. Analyse the cleaned dataset to see which customers completing the offers without viewing them
3. Select the better clustering method, between K-means & K-modes methods, using the Elbow method & Silhouette Scores
4. Apply the better clustering method to the dataset to identify the difference between the proportion of customers in each cluster that responded to an offer and the proportion of customers overall that responded to an offer, for each of the offers

Apart from the notebook in this repo, I also have a blog post [Your loyalty program is working? Think again.](https://medium.com/@sandytat22/your-loyalty-program-is-working-think-again-e6d2e3d74c03) which I use to emphasise the importance of relevancy and personalisation in marketing promotions.

You can find the link to my blog post here on Medium: [Your loyalty program is working? Think again.](https://medium.com/@sandytat22/your-loyalty-program-is-working-think-again-e6d2e3d74c03)

**The two key questions I raised in the blog post are:**
1. If your customers make repeat purchases because of the offers?
2. If your customers like all kind of offers you send them?

**Findings:**
1. The K-means method is better suit our dataset
2. We can best group the customers into 8 groups, and they have different level of engagement with specific type of offers
3. We can estimate that at least 40% of offers received across all offer types were completed without viewing. 
4. Groups of customers (clusters 0, 1 & 3) who have the average transaction value of 20 dollars or more, have an average of at least 3 completed offers but not view. And nearly 50% or more customers in these 3 groups are female, compared to other groups have avg. 45% or less female.


### Files in the repository:
In the data folder:
- portfolio.json file — contains offer ids and their details
- profile.json file — demographic data or each customer
- transcript.json file — records for transactions, offer received, viewed and completed

### Requirements
**Libraries used:**
- Pandas
- Numpy
- Math
- Json
- Datetime
- Seaborn
- Matplotlib


