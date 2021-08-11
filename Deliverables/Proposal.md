## Project Proposal
Authored by Jon Yu \
on August 11, 2021

### Question/need:

If you're a regular Amazon customer who has purchased non brand name electronics products in recent years, you may have been shocked to see your delivered products accompanied by a solicitation to leave 5-star reviews in return for a gift card. Additionally, Amazon product review database is frequently plagued with fake reviews from dummy customer accounts. Yet another variation of the deceptive review manipulation is financially incentivizing customers who leave 1-star reviews to remove such reviews (https://www.wsj.com/articles/when-amazon-customers-leave-negative-reviews-some-sellers-hunt-them-down-11628420400).

The motivation behind this project is to utilize primarily text based data set in order to perform natural language processing and spot fake reviews, in hopes of implementing a recommender system for product searches taking into consideration the percentage of "honest" reviews correlated with the average rating. The final implementation will be my own iteration of currently existing tools such as ReviewMeta and FakeSpot.

### Data:

Primary data set will be Amazon customer reviews for electronics category (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Electronics_v1_00.tsv.gz).

I will attempt to locate review data sets for vendors who have been banned from the platform for abusing the review system.

### Tools: 

* AWS for data storage and query
* MongoDB for exploratory data analysis and cleaning
* spaCy or NLTK for text processing 
* MatPlotLib and Seaborn to plot data for correlation analysis
* LDA, LSA, NMF for topic modeling
If time allows, Streamlit will be utilized to deploy the visualization results through a web app.
Python text processing libraries/tools (such as NLTK, spaCy, gensim, scikit-learn) are required for data handling.

### MVP Goal:

The minimum viable product (MVP) will be cluster modeling of the preprocessed text data.
