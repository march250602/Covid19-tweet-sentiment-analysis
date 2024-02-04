# Covid19-tweet-sentiment-analysis
This project focuses on analyzing sentiments in Covid-19 related tweets using a Convolutional Neural Network (CNN) in Python, specifically within Jupyter Notebook. We'll use key libraries like 
-pandas 
-numpy
-matplotlib
-seaborn
-sklearn 
-tensorflow 
-nltk
for data manipulation, visualization, and machine learning.

# Data Collection and Preprocessing
Clean and remove urls, html tags, digits, hashtags, mentions, and stop words using nltk.corpus

<img width="614" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/57da4a75-9852-4e00-8071-d64a127aec9f">

Implement a tokenizer to break down text data into tokens. This can enhance the efficiency of machine learning model.

<img width="368" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/39c77e7c-5682-42b7-ae0f-478ced545979">



# Explore Data
Use Matplotlib to visualize the distribution of sentiment within the training data.

<img width="373" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/9787bda7-c0b9-42b3-b022-16c89aef9ad4">

# Machine Learning Model
Implement a CNN using TensorFlow for sentiment analysis

<img width="429" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/4800364d-35d6-446f-ad5e-de550e772b93">

# Model Evaluation
<img width="428" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/2279fe25-b387-41ff-984b-9a385ebcc24c">


<img width="361" alt="image" src="https://github.com/march250602/Covid19-tweet-sentiment-analysis/assets/68798300/2a5b2bc8-253d-4987-b1d1-0cfa85945569">


The plots above show that the intended number of epochs is 15, but after the second epoch, the model starts to have its val_accuracy tend to decrease and its val_loss tend to increase.
Despite the fact that accuracy is likely to decrease, the model shows high test accuracy at 83.6% and test loss at 0.5.

