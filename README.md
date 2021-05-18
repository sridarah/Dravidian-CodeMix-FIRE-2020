# Dravidian-CodeMix-FIRE-2020
This repository contains our (HRS-TECHIE) submissions to the Dravidian-CodeMix competetion which  is "Sentimental analysis of Dravidian languages ( Tamil ) in Code-MixedText" at FIRE 2020.

# Team Members
Sridhar Swaminathan, Hari Krishnan Ganesan, and Radhakrishnan Pandiyarajan

# Publication
Sridhar Swaminathan, Hari Krishnan Ganesan, and Radhakrishnan Pandiyarajan, "HRS-TECHIE@HASOC 2020: Identification of Hate Speech and Offensive Content in Twitter using state-of-the-art Machine Learning, Deep Learning and Ensemble Methods", 12th Forum for Information Retrieval Evaluation, 2020. (Rank 12 and 9)
 
# About Dravidian-CodeMix-FIRE2020
Sentiment analysis is the task of identifying subjective opinions or responses about a given topic. It has been an active area of research in the past two decades in both academia and industry. There is an increasing demand for sentiment analysis on social media texts which are largely code-mixed. Code-mixing is a prevalent phenomenon in a multilingual community and the code-mixed texts are sometimes written in non-native scripts. Systems trained on monolingual data fail on code-mixed data due to the complexity of code-switching at different linguistic levels in the text. This shared task presents a new gold standard corpus for sentiment analysis of code-mixed text in Dravidian languages (Malayalam-English and Tamil-English).

The goal of this task is to identify sentiment polarity of the code-mixed dataset of comments/posts in Dravidian Languages (Malayalam-English and Tamil-English) collected from social media. The comment/post may contain more than one sentence but the average sentence length of the corpora is 1. Each comment/post is annotated with sentiment polarity at the comment/post level. This dataset also has class imbalance problems depicting real-world scenarios. Our proposal aims to encourage research that will reveal how sentiment is expressed in code-mixed scenarios on social media.

# Dataset
 There are 3 types of datasets for Tamil-English mixed text collected from Youtube given by competition organizers.
       1. Training set 
       2. Validation set 
       3. Test set 
      
  Totally,15744 comments are available. From this, Training set contains 11,335 comments , Validation set contains 1,260 comments and Test set contains 3,149 comments. All comments are divided into 5 types of classes / labels. Which are,
        1. not-Tamil
        2. unknown_state
        3. Positive
        4. Mixed_feelings
        5. Negative

# Our Submissions
 We develped the Machine learning , Deep learning and Ensemble methodology ( Max voting ) based classifiers for the Tamil-English Mixed data.
 
 This repo contains two IPython Notebooks which are containing the code for develop the classifiers to the challenge. 
        1. Sentimental analysis using LSTM.ipynb
        2. Sentimental analysis using ML and Ensemble.ipynb
  
  # 1. Sentimental analysis using LSTM.ipynb
   This notebook contains the code for reading the dataset,preprocessing of comments , creating custom word embedding , creating LSTM model , training and predicting the  labels of the test data.     

  # 2. Sentimental analysis using ML and Ensemble.ipynb
   This notebook contains the code for reading the dataset,preprocessing of comments , creating TF-IDF vectors, creating Machine learning models (Naive Bayes , Decision tree, Random Forest ,AdaBoost+Decision Tree)/ Ensemble model ( Max voting of 4 ML classifiers) , training and predicting the labels of the test data.

# Results
   Naive Bayes classifier achieves the highest weighted average F1-score 0.61 compare than our other classifiers and got 5th rank in the leaderboard.
   

