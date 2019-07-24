# Landmark-Recognition
The project used "Transfer Learning" in the lankmark recognition task. As the training set has only 27,000 samples, building a neural network from scratch can only get a poor performance.

### Details
For baseline model, the result was achieved by training a model using ResNet18 for 15 minutes on AWS with cuda GPU.
For the chosen model, the result was achieved by training a model using training on the pre-trained weights of ResNet50 for 1 hour on AWS with cuda GPU.


### Result
The accuracy of baseline is 88.3%. The accuracy of the best model is 98.9%, which is a quite good performance.
