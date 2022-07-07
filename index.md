## Data Science Projects

---

### CNN Image Classification 

[Dog Breed Classifer](https://github.com/lgonzal6/dog_breed_classifier)
<img src="images/dog_collage2.png?raw=true"/>

#### Description
Dog shelters suffer from a high rate of dog breed misclassifications. Dog breeds, however, can provide import insight into a dog’s health and behavioral predispositions. Therefore, I sought to test whether a Convolutional Neural Network can improve breed classification rates. I used InceptionV3 for the model’s architecture, paired with EarlyStop and ReduceLROnPlateau. For the training and validation images, I used the Stanford Dog Dataset. Despite several issues with the dataset, the model achieved an 86% accuracy across all breeds, furthermore, 60% of breeds had recall scores of 90% or more. Please visit my Github repository for more information.


---
[Wildlife Image Classification](https://github.com/lgonzal6/Wildlife_Image_Classification)
<img src="images/wild_life2.jpeg?raw=true"/>

#### Description
Conservationist at Tai National Park have set up camera traps at 148 sites throughout the park in order to study the animals that call the park home. The camera traps are meant to capture pictures of these animals and are triggered by movement or heat. It’s not easy for conservationist to go through thousands of photos and identify the species in each frame. Therefore, our team set out to train a CNN model to identify seven different animal species (and blank images). Images from the cameras presented many challenges, for instance, many images were taken at night, many images were not focused, and some only showed a partial image of the animal. Due to such difficulties, our model achieved an accuracy score of 46%. Nonetheless, this project highlights methods including transfer learning, data augmentation, and multiclass classification metrics.


---
### Natural Language Processing (NLP)

[Tacobell Subreddit NLP](https://github.com/lgonzal6/tacobell_reddit_nlp)
<img src="images/reddit.jpeg?raw=true"/>
#### Description
Taco Bell holds the largest share of the Mexican-style restaurant market in the U.S. A main driver of Taco Bell’s success is their product innovation. While Taco Bell has successfully incorporated popular elements of Mexican cuisine to craft an exciting menu, this project incorporates Natural Language Processing to search for other elements of Mexican cuisine that is currently missing at Taco Bell. This project pulls posts from the r/tacobell and r/mexicanfood subreddits to compare popular food items in both groups. By building models that can distinguish post from both subreddits with a 90% accuracy, we are able to extract food items that are most distinctive of each group, and thereby highlight popular Mexican food items that are missing from Taco Bell’s menu. 

---
### Recommender System

[Netflix Recommnder System with Surprise Library](https://github.com/lgonzal6/netflix_recommender_surprise)
<img src="images/dog_collage2.png?raw=true"/>

#### Description
This project explores Netflix's movie database and creates a recommender system using collaborative filtering. The data included Movie_ID, User_ID, and Rating (1 - 5 scale). To create the the recommender system, we used the Surprise library created by Nicolas Hug. We compare results from three different algorithms: BaselineOnly, KNNWithMeans, and SVD. After obtaining the best rmse score from using SVD, we fine-tuned further using gridsearch. The resulting algorithm resulted in a rmse of 0.88, and a mae of 0.70. Further exploring the errors revealed that the vast majority of ratings were mispredicted by 1 ratign point or less. 

---
### Regression Analysis 

[Aimes, IO Housing Analysis](https://github.com/lgonzal6/aimes_iowa_housing)
<img src="images/housing.jpeg?raw=true"/>

#### Description 

Home sellers desire to optimize the sale price for their homes. Many seek to increase home values by making home improvement and renovations . These projects, however, can be very costly and owners should undertake such investment only if they can reasonably expect the home price to increase by a larger dollar amount than the cost of the project. This project analysis home sale data to estimate the home value increase related to home improvements. Owners can then use the results from this analysis to determine whether there is a financial benefit to certain renovation projects.

---
