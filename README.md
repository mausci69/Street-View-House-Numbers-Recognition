Image classifier for the SVHN dataset

In this Capstone for the 1st Course of the Tensorflow 2 Specialization from the London Imperial College released in Coursera, I created two neural networks that 
classified real-world images digits. The 1st Neural Network is an MLP (Multi-Layer Perceptron), composed of a Flatten layer, to reduce the 2D of the images in 1D, 
and then 4 Dense Layers. With this network, I didn't make use of any regularization technique, as requested by the test itself. The 2nd Neural Network is a more
complex CNN (Convolutional Neural Network), with two Conv2D Layers, BatchNormalization, Dropout and Flatten Layers. Even though I've trained this network just 
for 15 epochs, half of the 30 epochs I trained my MLP for, I reached almost half of the loss value for the Validation Set. At the end, I checked these networks 
with a few of the data, to see how they work.
