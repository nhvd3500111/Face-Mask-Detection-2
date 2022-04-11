# Face-Mask-Detection-2
Face Mask Detection using OpenCV and Tensorflow/Keras. Dataset from https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

Creation of a Model that recieves a picture and performs multi class classification (idientifies whether a person wears a mask properly, wears a mask the wrong way or doe snot wear a mask at all)

***IMPORTANT***
-----------------------
Please eaxecute the three notebooks as mentioned in their name one after another. Save them in the same directory as the dataset's folder. 
More specifically, if each notebook is saved in the path ......./directory/notebook, then the above mentioned directory of the dataset (kaggle) must be saved saved in the path ....../directory/kaggle.... of your local pc
-----------------------

1st Notebook: Preprocessing of the Data, Data Augmentation, Development of three different types of DNNs to exploit them later in order to avoid GAN attacks

(CNN with random activation functions, CNN with Lecun activation function and a MobilnetV2 on top of which we add extra layers)

2nd Notebook:
