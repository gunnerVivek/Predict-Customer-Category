# Predict the Category of the Customer

## Problem Statement
We all know that when we visit an e-commerce or TV series website or even YouTube we see a separate suggestion box, where in they show some content which you might like. These are mainly based on the content that you have consumed on their website previously. These are called as Recommendation engine. 

Now consider you have been running a start up since last one year and now you have been able to gather some customer data and you want to build a recommendation engine. Based on certain features you have to cluster the customers into two different groups so that you can recommend the correct products based on the customer’s cluster.

## Challenge
Your work is to build a predictive model to predict the category of the customer. You have to predict the column : “customer_category”
You need to upload a presentation proposal addressing the following questions:
- What are the pros & cons of recommendation by this approach?

- Propose an architecture that will work more efficiently when building a recommendation engine for an e-commerce platform

## Data Descriptiuon

Column | Description |
------ | ----------- |
customer_visit_score | a score based on how regularly the customer visits the website |
customer_product_search_score | quality or price range of product that the customer searches for. For ex: a customer searching for a laptop will have more weightage than someone looking for a book |
customer_ctr_score	| how many of the searched links does the customer click|
customer_stay_score	 | a score based on the time spent on an average by the customer |
customer_frequency_score | a score based on how many times in a day the customer visit the website
customer_product_variation_score |	a score based on how many varities of products does a customer search for, for ex. electronics, apparels, etc.|
customer_order_score	| Score based on the no. of orders that has been succesfully delivered and not returned
customer_affinity_score	| an internal overall score calculated which signifies the affinity of the customer towards the website |
customer_active_segment | the categorization of the customers based on their activity |
X_1 |	Anonymized feature based on loyalty of the customer |
customer_category	(**Target**)| the cluster/group to which the customer should belong to |

### Data Files:

- Train.csv : 10378 x 10

- Test.csv : 7161 x 9

## Evaluation Criteria
- Please note the evaluation metric for score generation will be macro precision-score\
```
score  = precision_score(actual_values, predicted_values, average='macro')
```
- Evaluation metric for the source code & presentation submitted is as follows:

    - Approach: How well is the problem statement understood and attended to?

    - Creativity: Depth of Analysis

    - Visualisations: What features are being presented and how?

    Total Score (10+10+10 = 30)

