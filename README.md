# Digit_Recognizer
# This is ANN deep learning model to recognize hand written digits.
# Input - (784,)
# layer1 - 256 units, relu
# layer2 - 84 units, relu
# layer3 - 10 units, softmax
# Data set:  MNIST

# digit_recognizer_cnn
# This is a CNN deep learning model to recognize handwritten digits.
# Input - (None,28,28,1)
# Conv1 - filters=32 ; kernel_size=(3,3) ; padding='same' ; strides=1
# Maxpool_1 - (2,2) ; strides=2 ; padding='valid'
# Conv2 - filters=32 ; kernel_size=(3,3) ; padding='same' ; strides=1
# Maxpool_2 - (2,2) ; strides=2 ; padding='valid'
# Dropout layer - Dropout_prob = 0.2
# Flatten layer
# Fully Connected layer1 - 128 units, relu
# Fully Connected layer2 - 10 units, softmax

