# Background
Kaggle competetion link : https://www.kaggle.com/c/dic487-587
This project is about predictive analysis using Apace spark on the movie dataset. The genre was predicted from movie plot through text embedding. There are three models starting from basic model which uses count vectorizer, then this model was improvised by using TF -IDF, the last model uses custom features engineering(there are many techniques, but I used wordToVec here). Gradual increase in efficiency was observed starting from the basic model to wordvec. 

Basic Model     83.73%
Tf Idf Model    87.35%
Custom Features Model   93.12%

# Setup
The train and test data are separately uploaded. Replace the file path in the code with the respective paths where these files are stored in your system. 
Pyspark 2.4
java 8
python 3.7

The folder contains three csv files which are output of the three models. 
