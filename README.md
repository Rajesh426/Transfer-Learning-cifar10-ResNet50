# Transfer-Learning-
Its is a simple code which implement Transfer learning concept on cifar10 dataset using pre trained ResNet50
Here It uses pre trained ResNet50 for classifying cifar10 data set since ResNet50 is trained for 50 categories we will remove the 
last layer and we will add the last softmax layer to classify 10 categories of the cifar10 dataset. 
The dimension of the cifar10 is 32X32X3 which does not match the dimensionality required for training the ResNet50 so we will reshape the 
Dataset to 200X200X3 to suits the ResNet50 pretrained model. 
