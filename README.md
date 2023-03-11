This project aims to classify German traffic signs using a Convolutional Neural Network (CNN). The project uses the German Traffic Sign Recognition Benchmark dataset, which includes over 50,000 images of 43 different types of traffic signs.

The code is written in Python 3 and uses the TensorFlow library to create and train the CNN.

Dataset

The dataset used in this project can be found at https://bitbucket.org/jadslim/german-traffic-signs/src/master/test.p. The dataset is provided as a pickle file and contains 12,630 images of 43 different types of traffic signs.

The dataset is split into training, validation, and testing sets, with 80% of the data used for training, 10% for validation, and 10% for testing.

CNN Architecture

The CNN used in this project consists of the following layers:

Input layer
Convolutional layer with 32 filters
ReLU activation layer
Max pooling layer with a pool size of 2x2
Convolutional layer with 64 filters
ReLU activation layer
Max pooling layer with a pool size of 2x2
Flatten layer
Fully connected layer with 128 units
ReLU activation layer
Dropout layer with a rate of 0.5
Output layer with 43 units (one for each class)
Results

The model was trained for 15 epochs, and achieved an accuracy of 97.2% on the validation set and 96.9% on the test set.

The model's performance was evaluated on the test set using the following metrics:

Accuracy: 0.969
Precision: 0.968
Recall: 0.968
F1 Score: 0.968
