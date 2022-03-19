# Ecommerce_price

With over 10 GB of data we tried to predict the price of ecommerce goods during the first outbreak of covid which was during the month of March in 2020. This was a regression problem where we used three different models (Random Forest, Gradient Boosing Tree, Linear Regression) to make predictions. This also allowed us to compare these model's performances as well and how one model might be better to use due to needing less data preprocessing. In this project we used PySpark, MongoDB, and spark MLlib.

### Data preprocessing process:
1. We hosted CSV file on S3 buckets. Then We used PySpark to read it and merge it with a covid dataset (also hosted on S3).
2. Next we wrote the merged data to MongoDB to host the data on clusters.
3. We then worked on cleaning up the data and getting it ready to run ML models on it.

### ML models:
1. We ran three models of Gradient Boosing Tree, Random Forest, and Linear Regression.
2. We used accuracy as our metric to evaluate our models.
3. We were able to achieve an accuracy of 64.75 % by using Gradient Boosing Tree


I wroked on this project along with my friends Arman H. and Neset.
