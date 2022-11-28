# Glasses-or-not
Yeah!! This is an amazing model to classify a person with or without glasses

#### Well Neural Networks are amazing find of technological sector. The name itself suggest that it has is related to the neurons of human brain. But How it is developed is quiet interesting!!

- With the advancement it research of Neural Networks Different Networks are developed to work with like RNN-LSTM works well in NLP based works, ANN can be used for simple regression/classication and CNN can be used for Image Processing and related works, which is what we are going to look after.

#### We have prepared a model to classify the images of person wearing glasses or not.

For the same we have prepared CNN model explaining every components of the same. So, let's Understand the CNN 

### CONVOLUTIONAL NEURAL NETWORK:
- A deep learning CNN mainly consists of : a convolutional layer,a activation layer, a pooling layer and a output layer. The convolutional layer is the first layer while the output layer is the last.

### CONVOLUTIONAL LAYER:
- The majority of work happens in the convolutional layer, which is the core building block of a CNN. A second convolutional layer can follow the initial convolutional layer. The process of convolution involves a kernel or filter inside this layer moving across the receptive fields of the image, checking if a feature is present in the image.

- Over multiple iterations, the kernel sweeps over the entire image. After each iteration a dot product is calculated between the input pixels and the filter. The final output from the series of dots is known as a feature map or convolved feature. Ultimately, the image is converted into numerical values in this layer, which allows the CNN to interpret the image and extract relevant patterns from it.

### ACTIVATION LAYER:
- It is used to determine the output of neural network like yes or no. It maps the resulting values in between 0 to 1 or -1 to 1 etc. (depending upon the function).
Some examples of activation function are Sigmoid, ReLU, Leaky ReLU, Hyperbolic Tangent, Step Function..etc

### POOLING LAYER:
- In a pooling layer, all the values of the pixels in each feature map are ‘pooled’ together. This reduces the resolution of the feature maps from the convolution layers. The smaller representation of the images means fewer parameters and less computation.

### FULLY CONNECTED LAYER :
- Last, a CNN has fully connected layers. In a convolutional layer, the nodes only receive or share information from part of the layer before it. In a fully connected layer, every node receives the input from every node in the previous layer.

- Fully connected layers are like those you would find in the hidden layers of an artificial neural network. This is where all the features extracted by the convolutional neural network get combined. This means that the computer sees the whole image — which can help with generating an accurate output.


### EPOCH
- One Epoch is when an ENTIRE dataset is passed forward and backward through the neural network only ONCE.
So, it is related with gradient descent more the number of epochs more it will pass through gradient descent.
### BATCH SIZE
- As we know, we can’t pass the entire dataset into the neural net at once. So, you divide dataset into Number of Batches or sets or parts.
- Batch Size is Total number of training examples present in a single batch.

### BATCH NORMALIZATION
- it is a Normalization method used after activation function to normalize the data for faster and better result.
