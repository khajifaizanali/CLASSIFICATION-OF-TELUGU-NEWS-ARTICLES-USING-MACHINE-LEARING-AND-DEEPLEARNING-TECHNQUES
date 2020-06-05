# CLASSIFICATION-OF-TELUGU-NEWS-ARTICLES-USING-MACHINE-LEARING-AND-DEEPLEARNING-TECHNQUES
Deep Learning and Machine Learning techniques are used to Increase the performance of Classification of artricles
## Scrapping of dataset
Dataset used in this project is scrapped from the News Website. All articles from different categories are Scrapped and saved in the directory. Beautiful Soup library is used in this project to scrap. This Library helped us in parsing Html content and get Articles which are useful for Training and Testing. Below Shown figure is the basic output of scrapped articles with their links in Jupyter Note Book.
## Loading Training And Test Data
The Dataset Scrapped in Previous step is Split into train and test data. Train Dataset is used for Training Classifier and Test Data is used for validating the classifiers we have modelled. In this module, We are going to Load all train and test data in Dictionary.
## Building Stop Words
As to get a better accuracy we need to remove all stop words from articles. Stop words does not has much impact in training. So, we remove these words. In our project we have used  1000 common words in Telugu as stop words. We have even added Punctuations as stop words in our project. Punctuations in Telugu and English is almost similar.so, We can use normal English punctuations as stop words.
## Stemming of News Articles and Building Bag of Word Model
In This module All articles are Stemmed into root words. Stemming of the articles in increasing the accuracy. In our Project we have used Porter Stemmer to Stem the words in Telugu.

Using  Scikit Learn Library we can build Bag of words model. Count Vectorizer function is used to build the BoW model.

## Building Classifier Using Machine Learning Techniques- SVC, MULTI NAIVE BAYES, RANDOM FOREST CLASSIFIER
### Support Vector Classifier
A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples. In our Project we have used Scikit library to Build and fit the model.
### Multi Nominal Naïve Bayes Classification
Naive Bayes classifier is a general term which refers to conditional independence of each of the features in the model, while Multinomial Naive Bayes classifier is a specific instance of a Naive Bayes classifier which uses a multinomial distribution for each of the features. In our Project we have used Scikit library to Build and fit the model.
### Random Forest Classifier:
Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operate by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification). In our Project we have used Scikit library to Build and fit the model.
## BuildingDeep Neural Network Architecture 
Deep Learning uses a Neural Network to imitate animal intelligence. There are three types of layers of neurons in a neural network: the Input Layer, the Hidden Layer(s), and the Output Layer. Connections between neurons are associated with a weight, dictating the importance of the input value. In our Project we have used Kera’s to build architecture and train the classifier. The Architecture used for this Project is shown in the Image Below
## Validation of Built Classifiers
	The Classifiers are Validated with Test Dataset and Best Algorithm is chosen. 
	The Classification Reports of Various classifiers are Genrated.

 


