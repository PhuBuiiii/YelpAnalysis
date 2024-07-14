# Yelp-Review-Analysis
Dataset:  https://www.kaggle.com/yelp-dataset/yelp-dataset

# 1.Overall Project:
Yelp is an application to provide the platform for customers to write reviews and provide a star-rating. A research indicates that a one-star increase led to 59% increase in revenue of independent restaurants. Therefore, we see great potential of Yelp dataset as a valuable insights repository.

The main purpose of our project is to conduct thorough analysis on 7 different cuisine types of restaurants which are Korean, Japanese, Chinese, Vietnamese,Thai, French and Italian, figure out what makes a good restaurant and what concerns customers, and then make recommendations of the future improvement and profit growth. Specifically, we will mainly analyze customers' reviews and figure out reasons why customers love or dislike the restaurant.

# 2.Description of Data:
The Yelp dataset is downloaded from Kaggle website. In total, there are 5,200,000 user reviews, information on 174,000 business. we will focus on two tables which are business table and review table.

Attributes of business table are as following:

   - business_id: ID of the business
   - name: name of the business
   - neighborhood
   - address: address of the business
   - city: city of the business
   - state: state of the business
   - postal_code: postal code of the business
   - latitude: latitude of the business
   - longitude: longitude of the business
   - stars: average rating of the business
   - review_count: number of reviews received
   - is_open: 1 if the business is open, 0 therwise
   - categories: multiple categories of the business

Attribues of review table are as following:

   - review_id: ID of the review
   - user_id: ID of the user
   - business_id: ID of the business
   - stars: ratings of the business
   - date: review date
   - text: review from the user
   - useful: number of users who vote a review as usefull
   - funny: number of users who vote a review as funny
   - cool: number of users who vote a review as cool
# 3.Direction of Analysis
Exploratory data analysis:
   - Count the number of each cuisine type of restaurants
   - Count the number of reviews in each cuisine type of restaurants
   - Visualize the distribution of restaurants according to the ratings and cuisine types of restaurants.
Review Analysis:

   - Clean the category column in business table into different cuisine types of restaurants and find out how the reviews can help this type of restaurants improve in the future.
   - Refer the business id in business table to review table, collect all the reviews of this type of restaurants and perform sentiment analysis to analyze frequent words in positive and negative reviews.
   - Implement SVM model to get relatively positive and negative words and get score of each word.
   - Get top 10 positive words and negative words in each cuisine type of restaurants in order to figure out the reason of high score and low score.
   - Compare among different types of restaurants to figure out the advantages and disadvantages, then we can generate a series of recommendations to this type of restaurants for the future development.
   - Overall, recommendations may have different topics which is but not limited to service, food, or decoration, etc. Our analysis is generally based on review words which we can tell from such as rude, overpriced, and slow to find out which aspect in this type of restaurants that they could improve.

