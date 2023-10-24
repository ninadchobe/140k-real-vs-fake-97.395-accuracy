# 140k-real-vs-fake-97.395-accuracy
Data preprocessing and CNN classification on 140k real vs fake images dataset
There are two jupyter files for separate purposes. One for training and saving the model along with data importing and preprocessing. The base model used is the densenet121 due to its high effeciency. The model is trained on 20 epochs and stops at 8th epoch. 
The other file imports the model as json and h5 files and uses it to predict the images wheather they are fake or real. The testing accuracy achieved is 97.4
Link to the dataset used : https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
