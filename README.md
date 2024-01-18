# Twitter-Political-Sentiment


**Classification of Tweets from Northern Europe**

This project presents an analysis of tweets by politicians from seven Northern European countries (Belgium, Denmark, Iceland, Ireland, Netherlands, Norway, and Sweden). The focus was on comparing the features of these tweets and applying multiple clustering models. A Random Forest model was trained and validated, achieving an accuracy of 0.61, outperforming other models like Logistic Regression and Naive Bayes.

**Introduction**:
The dataset comprises tweets posted by politicians from the specified Northern European countries, provided by the Kaggle challenge. After data refinement and preliminary analysis, insights into political views, gender distribution, and common hashtags were drawn.

**Data**

  Dataset Size: 509,031 tweets (20% for training, 80% for testing).
  Features:
  Hashtags
      - Full text of tweets
      - User reply screen names
      - Country of the tweet’s owner
      - Political view of the tweet’s owner
      - Tweet ID
      
**Preliminary Analysis:**

Included examination of tweet and hashtag lengths, common hashtags, political views, and gender distribution among the tweet posters.

**Methodology**

Clustering Models: NMF (Non-Negative Matrix Factorization) and LDA (Latent Dirichlet Allocation) were used for topic generation.

Model Training: The Random Forest classifier was employed, with preprocessing steps including text cleaning, label encoding, tf-idf vectorization, and class weight balancing.

**Results**
Random Forest Model: Achieved an accuracy of 0.61.
Comparison with Other Models:
    Logistic Regression: 0.57 accuracy.
    Naive Bayes: 0.53 accuracy.
Evaluation Metrics: Accuracy, confusion matrix, and classification report.

**Discussion**
The project explored the use of different machine learning models to classify tweets from Northern European politicians. The Random Forest model demonstrated superior performance in accurately classifying these tweets, with a significant focus on political views, gender distribution, and the impact of current events as reflected in the hashtags.
