# Fashion Articles Classification

In the following notebook we will be analysing the dataset from the fashion-mnist dataset.

The framework being used for the machine learning is Keras.

The model has the following structure:

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_7 (Conv2D)            (None, 1, 28, 32)         3616      
_________________________________________________________________
activation_7 (Activation)    (None, 1, 28, 32)         0         
_________________________________________________________________
max_pooling2d_7 (MaxPooling2 (None, 1, 14, 32)         0         
_________________________________________________________________
conv2d_8 (Conv2D)            (None, 1, 14, 64)         8256      
_________________________________________________________________
activation_8 (Activation)    (None, 1, 14, 64)         0         
_________________________________________________________________
max_pooling2d_8 (MaxPooling2 (None, 1, 7, 64)          0         
_________________________________________________________________
flatten_4 (Flatten)          (None, 448)               0         
_________________________________________________________________
dense_5 (Dense)              (None, 128)               57472     
_________________________________________________________________
dense_6 (Dense)              (None, 10)                1290      
=================================================================
Total params: 70,634
Trainable params: 70,634
Non-trainable params: 0
_________________________________________________________________
```
