# CS3244 (Machine Learning Project - "Buttersnapped")

This project involves training different machine learning / deep learning models to predict the species of different butterflies. 
The butterfly images were obtained using Python's flickrAPI package, as well as one of the APIs provided by Flickr. 

`cnnModel`: The proposed model; a convolutional neural network whose hyperparameters were tuned. Best CNN model had a great performance, where the top-1 accuracy was 97.1% and top-3 accuracy was 100% respectively. 
`data/scripts`: the different scripts used when reading the image files in the data folders
`MLP.ipynb`: A multilayer perceptron from Python's sklearn package which was trained using the butterfly images.
`SVM.py': The baseline model which was used. The sklearn.svm.SVC function was used, where a linear kernel was used. 
