# SocialMediaPhotos-RecommendationSystem-MatrixFactorization

(Go to https://github.com/DanielTranDS/SocialMediaPhotos-RecommendationSystem-MatrixFactorization/blob/main/RecommendationSystem_Codes.ipynb for implementation)

Social media platforms produce a huge volume of semi-structured data. This provides a valuable and rich source of data to be analysed, which can potentially output insightful information about users and products. Companies can make use of this to further optimize their business.

In this project, I have semi-structured data in the form of social media photos. I will attempt to create a personalized recommendation system to recommend a list of photos to each user.

The information regarding the datasets used for this project is as follows:

Train data: The training dataset contains a set of interactions between users and items (photos). If a user liked a photo (e.g., click the "heart" emoji which indicates a positive engagement), then there will be a record in the dataset.

Test data: Each user is provided with a list of 100 candidate photos in the test dataset. I will need to check the candidate list and recommend the top 15 photos for each user.

Validation data: A validation dataset that I will use to tune my models. The dataset format is similar to the Test dataset, except that the ground truth of the rating is given.

User feature data: Each user is represented as a 256-dimensional feature representation, which is the average of the image feature representations they liked in the training data.

Item feature data: Each photo is represented as a 256-dimensional embedding which is extracted from a pre-training deep learning framework.

Links data: If two users are friends, there will be a link between two users.
