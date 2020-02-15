# MNISTClassification-Using-Plain-Neural-Networks-with-Keras


In this excercise/mini project I am trying to classify the famous MNIST dataset.

Goal: Primary goal of this excercise is to equip myself with Keras set up with regards to the Plain Neural Network. Secondary goal is to achieve atleast 98% success in predicting the right labels for the MNIST Images.

Dataset: The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.The database is also widely used for training and testing in the field of machine learning. You can read more about the dataset here(https://en.wikipedia.org/wiki/MNIST_database). The data is downloaded(called) from the Keras' dataset library.

Approach: First the dataset is downloaded & I set up a model based on intuition. I then iterartively change the hyperparameters (such as the number of layers, number of units, whether or not to regaularize, what optimizer to use, how long to train etc.) as I try to improve the performance of the model.

Results: After going through several iterative process, the final model with 4 hidden layers and a total of 111146 of trainable parameters after 20 epochs of training using the adam optimizer has 99.63% training set accuracy and 98.15% test set accuracy.

Future Works: As there's still a gap of almost 1.5% between the train & test set accuracy, one can try follow the same iterartive process to reduce the variance or use Convolutional Neural Network.

