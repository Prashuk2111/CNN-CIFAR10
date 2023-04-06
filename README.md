# CNN-CIFAR10

Using your preferred deep learning library, train a small convolutional neural network (CNN) to classify images from the CIFAR10 dataset. Note that most libraries have utility functions to download and load this dataset (TensorFlow, PyTorch).
Using the API for loading the dataset will readily divide it into training and testing sets. Randomly sample 20% of the training set and use that as your new training set for the purposes of this problem. Use the test set from the original dataset for validation. Normalize your training and testing sets using Min-Max normalization.


1- Build a multi-layer perceptron with the following layers:
“*” Dense layer with 512 units and a sigmoid activation function
• Dense layer with 512 units and a sigmoid activation function
• Dense layer (output layer) with 10 units (representing 10 classes in the dataset) and a suitable activation function for the classification task


2- Build a Convolutional neural network with the following architecture:
• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function
• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function
• Flatten layer (to pass to the Fully Connected layers)
• Fully connected (Dense) layer with 512 units and a sigmoid activation function
• Fully connected layer with 512 units and a sigmoid activation function
• Dense layer (output layer) with 10 units and a suitable activation function for the classification task


3- Build a Convolutional Neural network with the following architecture:
• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function
• 2x2 Maxpooling layer 
• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function 2x2 Maxpooling layer
• Flatten layer (to pass to the Fully Connected layers)
• Fully connected (Dense) layer with 512 units and a sigmoid activation function Dropout layer with 0.2 dropout rate
• Fully connected layer with 512 units and a sigmoid activation function
• Dropout layer with 0.2 dropout rate
• Dense layer (output layer) with 10 units and a suitable activation function for the classification task


Use a batch size of 32, utilize Adam as the optimizer and choose an appropriate loss function while
monitoring the accuracy in both networks. Train each network for 5 epochs.
