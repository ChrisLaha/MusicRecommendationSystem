# MusicRecommendationSystem
* Create a music recommendation system
* Given a dataset of users, write code to find the Nearest Neighbor recommendations for user X based on Euclidean similarity measure
* Find artists that other users in the data set have rated to recommend artists that user X may also like
* Personlaize recommendations Utility Matrix - Model
* X = set of Customers
* I = Set of Items
---
![output](https://github.com/ChrisLaha/MusicRecommendationSystem/blob/main/images/recommender_systems.png?raw=true)
![output](https://github.com/ChrisLaha/MusicRecommendationSystem/blob/main/images/plan_of_action.png?raw=true)
![output](https://github.com/ChrisLaha/MusicRecommendationSystem/blob/main/images/recommendations.png?raw=true)
---
* Utility Function u: X * I -> R
* R = set of ratings
* R is a totally ordered set
* e.g., 0-5 Stars, real number [0,1]
![output](https://github.com/ChrisLaha/MusicRecommendationSystem/blob/main/images/utility_matrix.png?raw=true)
---
## Key Problems
1. Gathering "known" ratings for the matrix
* How to collect the data in the utility matrix
2. Extrapolate unknown ratings from the known ones
* Mainly interested in high unknown ratings
* We are not interested in knowing what you don't like but what you do like
3. Evaluating extrapolation methods
* How to measure success/performance of recommendation methods

