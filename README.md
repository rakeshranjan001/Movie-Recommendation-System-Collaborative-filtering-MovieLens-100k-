# Movie-Recommendation-System-Collaborative-filtering-MovieLens-100k-
Movie https://github.com/Shadow-9661/Movie-Recommendation-System-Collaborative-filtering-MovieLens-100k-/issuesRecommendation System , Collaborative Filtering
  
  Dataset Used : MovieLens 100k

# Item Based Collaborative Filtering

Item-item models use rating distributions per item, not per user. With more users than items, each item tends to have more ratings than each user, so an item's average rating usually doesn't change quickly. This leads to more stable rating distributions in the model, so the model doesn't have to be rebuilt as often. When users consume and then rate an item, that item's similar items are picked from the existing system model and added to the user's recommendations.

First, the system executes a model-building stage by finding the similarity between all pairs of items. This similarity function can take many forms, such as correlation between ratings or cosine of those rating vectors

Second, the system executes a recommendation stage. It uses the most similar items to a user's already-rated items to generate a list of recommendations
