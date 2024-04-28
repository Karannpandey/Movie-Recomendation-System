Movie Recommendation System

Team Members:
- Yash Koushik (IMT2020033)
- Surya Sastry (IMT2020079)
- Dharmin (IMT2020127)
- Karan Raj Pandey (IMT2021014)

---

Problem Statement:
The objective of this project is to build a movie recommendation system utilizing the MovieLens 1M dataset. The system aims to suggest new movies to users based on their existing reviews, employing techniques such as K-Means, Singular Value Decomposition (SVD), and Collaborative Filtering from scratch using only numpy and pandas libraries.

---

Dataset Overview:
- MovieLens 1M dataset contains approximately 1 million ratings of 4000 movies by over 6000 users.
- Divided into three files: users.dat, movies.dat, and ratings.dat.
- Users.dat includes user information like Gender, Age, Occupation, and Zipcode.
- Movies.dat contains movie details such as Title and Genre.
- Ratings.dat consists of user ratings for movies.

---

Exploratory Data Analysis (EDA):
- Explored rating distributions, user demographics, and genre preferences to gain insights.
- Identified patterns such as positive sentiment towards movies, age and gender distributions, and popular movie genres.

---

Helper Methods:
- Implemented K-Means centroid initialization techniques: Random, K-Means++, and Naive Sharding.
- Developed SVD methods from scratch including Reduced SVD.
- Utilized evaluation metrics like Mean Squared Error (MSE) for SVD+K-Means.

---

Different Approaches:
- SVD + K-Means
- Collaborative Filtering
- Hybrid Recommendation
- Temporal Recommendation

---

Preprocessing:
- One-hot encoding of Zip-codes and Occupation for user similarity metrics.
- Standardization of Age and normalization of Ratings for ease of processing.

---

SVD + K-Means Recommendation:
- Transformed dataset into a matrix with UserID as index and various features as columns.
- Used SVD to understand user preferences and generate recommendations.

---

Error Analysis:
- Predicted genres and calculated MSE between actual and recommended genres.
- Incorporated years as a genre for recommending.

---

Preprocessing for Collaborative Filtering:
- Implemented Bayesian Average and Pearson’s Correlation for handling the cold start problem.
- Converted genres into binary features and calculated movie similarity.

---

Collaborative Filtering:
- Transformed dataframe into user-item matrix.
- Utilized Item-Item recommendation using k-nearest neighbors.
- Evaluated sparsity of the data.

---

Dimensionality Reduction with Matrix Factorization:
- Employed Matrix Factorization to uncover latent features in user-movie interactions.

---

Novelties Implemented:
- Hybrid Recommendation combining collaborative and content-based filtering.
- Temporal Recommendation generating movie recommendations based on the time of day.

---

Output:
- Hybrid Recommendation function provides collaborative and content-based recommendations for a given movie title.
- Temporal Recommendation function offers movie recommendations based on the current time of day.

---

Conclusion:
The Movie Recommendation System offers personalized movie suggestions to users based on their preferences and the current time of day, enhancing user experience and engagement with the platform.

---

Note:
- Ensure proper installation of required libraries (numpy, pandas).
- Refer to the project documentation for detailed implementation and usage instructions.
