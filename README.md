# Cats-vs-Dog-Binary-Classification

This binary classifier was made using a Convolutional Nueral Networks which distinguishes the pictures of a cat and that of a dog.

### Architecture:
Made up of 8 convolution layers where after 2 of them a pooling layer is added and Batch Normalization was applied to all convolutional layers.
It is then flattened and passed to fully connecte neurons with 2 layers with 256 and 128 neurons respectively.

ReLU activation function is used in all layers except the final one where sigmoid is used to classify the images.
Optimizer Adam was used.
Dropout with p=0.1 was also applied to fully connected neurons.
