# sentiment-analysis-using-machine-learning
Consists of Python files that trains a model and uses a trained model to take input from user and predict the sentiment of the keyword.

Fulform of smsa-Social media sentiment Analysis.

Main_final_smsa.ipynb:Consists all the steps involved in the training of a model of MNB which is saved for further use. A training.1600000.processed.noemoticon.csv file is used to train the model. Basically this file consists of 16,00,000 tweets which are preprocessed, stemmed, vectorizer, and split into training and testing data to help train the model for predicting the sentiments. Since the datasets is too big, we have refrained from uploading it to the repository, you can find it in this website (https://www.kaggle.com/datasets/kazanova/sentiment140). Finally, user's can give input keyword of their choosing and the model will predict that keyword's sentiment accurately. The actual stemming of the text in the before mentioned csv file takes about a few hours, so it would be better to ues the saved model or one can execute the code on google colab which will reduce the amount of processing time. The accuracy of this model's prediction even though is near 90's, it's actually more than that as we've tested it quite a few number of times and it never seems to get things wrong. Here, 0 represents negative sentiment and 1 represents positive sentiment.

Main_final_front_smsa_application.ipynb: This is file is where we load our saved trained model along with vectorizer and ask for user input and provide appropriate output.

original+pythonapp.ipynb: This is the python file which consists of the Original Source Code that was provided to us in ML project list by TIE. I would like to state that the accuracy stated for the code was inaccurate as it's true accuracy was about 66% which you can confirm by opening the file.

vectorizer_pickle.sav, trained_model.sav: These are the files which are saved from the Main_final_smsa.ipynb and can be used anywhere as long as the file is available.

The remaining files such as Tweets, data, train, edit are csv files which are basically datasets that can be used to further train the saved model.

Finally I would like to thank Varcons Technologies and TIE for granting me this opportunity to work on this amazing project. It has truly helped me improve a lot of my skills and helped my get a good grasp on ML with python.
