# image-classification-horse-vs-human
image classification using convolutional neural networks, including transfer learning and image generator
initially downloaded dataset from coursera which produced excellent results on training set but performed very bad on the test set.
thought that it was only due to overfitting, but i decided to look through the training images. 
found out that the training data wasn't at all representative of the real test data that i gave it.
so created my own dataset and also used augmentation on it using keras image generator class.
to improve the results, used mobilenet network as the initial layers and added a small convnet on top of it. 
the resulting network showed to be much more correct in predicting the classes.
