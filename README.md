# Amazon_Food_Reviews_Featurization


# Amazon_Food_Reviews
In this repository, I am practiced and implemented various machine learning algorithms using the real-world dataset amazon food reviews from Kaggle.

![Amazon_Food_Reviews](https://miro.medium.com/max/523/1*bXDiOoCFTSJJdTQ7JbuijQ.png)

## Task 01. Amazon_Food_Reviews_Featurization

First and foremost, we'd like to know What is Amazon Fine Food Review Analysis, and how does it work?
This dataset contains Amazon reviews of exquisite meals. The data spans more than a decade, with all 500,000 reviews up to October 2012 included. Product and user information, ratings, and a plaintext review are all included in reviews. We also have feedback from all of Amazon's other categories.


Amazon evaluations are frequently the most visible consumer product reviews. As a frequent Amazon customer, I was intrigued by the idea of visualizing the structure of a vast collection of Amazon reviews in order to become a more informed consumer and reviewer.
Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

### Introduction

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

1. Number of reviews: 568,454
2. Number of users: 256,059
3. Number of products: 74,258
4. Timespan: Oct 1999 — Oct 2012
5. Number of Attributes/Columns in data: 10

### Attribute Information:
1. Id
2. ProductId — unique identifier for the product
3. UserId — unqiue identifier for the user
4. ProfileName
5. Helpfulness Numerator — number of users who found the review helpful
6. HelpfullnessDenominator — number of users who indicated whether they found the review helpful or not
7. Score — rating between 1 and 5
8. Time — timestamp for the review
9. Summary — brief summary of the review
10. Text — text of the review

## Objective
Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).

[Q] How to determine if a review is positive or negative?

[Ans] We might make use of the Score/Rating system. A 4 or 5 star rating could be considered a favourable review. A rating of 1 or 2 could be construed as unfavorable. A score of 3 indicates that the review is neutral and should be ignored. This is a rough and proximal method of determining a review's polarity (positivity/negativity).


