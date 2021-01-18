### Sentiment Analysis
This is a sentiment analysis task implemented in Google Colab with NLTK and TensorFlow. There are many problem which can be done more or less in similar fashion after understanding this task viz.
Twitter Sentiment Analysis, SMS Spam Detection Model, Movie Reviews Sentiment analysis, Amazon Product Reviews Sentiment Analysis, Fake News detection and so on.
#### Concepts covered:
1) Downloading data directly to colab from Kaggle
* Text data Cleaning and Pre-Processing
2) Replacing emoticons with equivalent text
3) Removing tags & URLs, stopwords, Punctuations, Alphanumeric character
4) Lemmmatize
* Data Exploration
5) Bar plot/count plot of positive negative words frequency
6) Word cloud for positive negative tweets
Steps 2 to 6 are common for most of the text analytics.
* Modeling Using DNN Tensorflow
7) Tokenization, Padding 
8) Using Glove Embedding Matrix
9) Training and validation accuracy plot
10) Sentiment prediction of any sentence given by the user.
* We can try a few other different combinations of layer/bidirectional layers and check for accuracy improvement.
* Note: We have to preprocess the input sentence (steps 2 to 4) at the time of prediction, which is not done here.
We can make a function and pass the sentence through it for carrying out all the pre-processing.
