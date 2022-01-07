# Keyword-detection-using-Qkeras
The Objective of this project is to detect the Key words- "down", "go", "left", "no", "right", "stop", "up" and "yes" from 1 second Audio clip using a Quantized layers in Qkeras.

# Motivation
The motivation of this project was to reduce the memory requirement for the Deep Learning model for Keyword Detection using a Quantized keras library called Qkeras.

Quantization allows the weights of the neural network to be represented by a reduced number of bits compared to the usual 32 bits using the mathematical technique of Quantization. This may lead to a reduced accuracy, however the accuracy may be improved by tweaking certain parameters of the model while training.
In this project, ternary quantization has been used which reduces the no. of bits required to represent the weights to three representing a postive value, negative value and zero.

# Dataset
The Data set used for training the network is a smaller version of the Speech Commands Dataset by Google.

# Running the Model
1. The model can be run by opening the .ipynb file using Google Colab.
2. The code for installing the dataset is also included in the Google Colab file.
3. A supporting presentation is also included in the repository explaining the results obtained.

# References
1. Qkeras Repository-https://github.com/google/qkeras
2. Keyword Detection using Keras- https://www.tensorflow.org/tutorials/audio/simple_audio
