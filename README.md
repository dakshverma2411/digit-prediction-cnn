# digit-prediction-cnn
Model, trained over 5000 images of handwriiten digits using convolutional neural networks 
Dataset (source: kaggle) contained 6144 images of handwritten digits from 0n to 9. Data set was split in training set and test set 
(approximately 20% of data in test set)
Architecture contains 3 conv layers out of which first  2 layers is followed by max pool layers.
Filter (or kernel size) of 3x3 and stride of 2 was used
After conv layers 3 dense layers were used that also undergone regularization (dropout)
Model was trained for just 100 epochs.
Accuracy graph of last 50 epochs is provided (accuracy.jpg)
As a result of such architect model got the training accuracy aof about 90 percent and test accuracy near to 80 percent.
