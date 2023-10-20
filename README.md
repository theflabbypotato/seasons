# seasons

Kaggle Data: https://www.kaggle.com/datasets/grubenm/austin-weather/

**Explanation:**
I wrote this code in the process of learning Tensor flow and machine learning algorithms.  I did previously learn a bit about some of the conceptual ideas behind machine learning algorithms, like the basics of linear regression, K-means clustering, etc. but I still had a lot to learn.  I used a lot of online resources to learn by myself and I spent like 10 ish hours over a week just trying to understand some of these concepts beforehand. Regarding the code, I had the features be all the other information, and the label be the date (which I converted into seasons).  I scaled the numerical features, filled in empty values, and also one-hot-encoded (a column for every unique value) for "events" column as it isn't numerical.  Then a made a model with two hidden layers using tensorflow that employed a dropout rate to make sure I wasn't overfitting.  Over 100 epochs, the accuracy reached around 70%, which is  better than the 25% but I still think there is certaintly still area for improvement.  All in all, I know my current knowledge isn't the strongest but I'm really eager and dedicated to continue learning.
