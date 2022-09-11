# lung-cancer-detection-using-CNN
For medical imaging so many different types of images are used but computer Tomography (CT) scans are generally preferred because of less noise. Deep learning is proven to be the best method for medical imaging, feature extraction and classification of objects. Several types of deep learning architectures are introduced by so many researchers to classify the lung cancer. CNN provides some advantage over other algorithms in lung cancer detection.

# Dataset
Real patients CT scan images are obtained from Lung Image Database Consortium (LIDC) archive. It is a database of Lung cancer screening CT images for development, training, and evaluation of computer assisted diagnostic methods for lung cancer detection and diagnosis. 

# Data Preprocessing 
Some noises are embedded on CT Images at the time of image acquisition process which aids in false detection of nodules. Therefore, these noises have to be removed for accurate detection of cancer. CT scan images are converted to grayscale images, in which the only colours are shades of grey. Information required to store for these greyscale images is quite low. CNN works well on grayscale images since it is easier to test and understand.

# CNN Model
CNN Model is built for lung cancer detection using keras. Convolutional neural network (CNNs) uses a multilayer system consists of the input layer, output layer, and a hidden layer that comprises multiple convolutional layers, pooling layers, fully connected layers. A convolutional neural network with seven hidden layers was implemented for this task. 
Dataset is divided into training data and testing data for training and testing the built model. 

# Detecting lung cancer
Takes a CT-scan image from the user. Preprocessing is performed to remove noise and then sent to the model which then classifies the tumor found in the image as beningn or maliganant or normal.
