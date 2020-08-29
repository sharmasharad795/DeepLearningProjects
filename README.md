# DeepLearningProjects
This repo contains some of my earliest deep learning projects along with the recent ones that I keep adding

# IMDB_BinaryClassification - 
Took text data and converted into floating point tensors for binary classification of reviews into positive and negative.
Used two hidden neural layers for this purpose.

# HouseRegression - 
Used two hidden layers along with K fold cross validation to predict house prices (regression using neural nets)

# MulticlassClassification_Reuters - 
Took text data from reuters and converted into floating point tensors for multiclass classification of reuters labels.
Used two hidden layers with a validation set.



# DogVsCatsClassification - 
My take on Kaggle's famous Image classification problem (https://www.kaggle.com/biaiscience/dogs-vs-cats)

Have created separate directories to differentiate between train,validate and test data sets for cats and dogs.

Approaches followed :
1) 4 layes of Convnets plus MaxPooling, fed into a densely connected classification layer

2) 4 layes of Convnets plus MaxPooling, fed into a densely connected classification layer + image augmentation to increase the training sample sie + dropout of 0.5 to prevent overfitting

3) Using VGG16 pre-trained network to extract features from our given dataset. The extracted features are then fed to a densely connected classifier of 1 hidden layer with a dropout of 0.5

