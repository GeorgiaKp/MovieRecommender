# MovieRecommender
Given a dataset of movies, users and ratings, predict the users' ratings for movies the will likely be interested but have not rated (seen).
A hybrid collaborative filtering system. At first the item-item system excludes movies for which the predicted rating is < 2.5/5. Then a user-user system makes the final predictions of ratings.<br>
For similarity functions, adjusted cosine and jaccard are used and compared.
