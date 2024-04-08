# CNN-using-transfer-learning

This model implements the Inceptionet model for feature extraction, that was originally created by Google for use in GoogLeNet. This is the backbone for the entire model, the first few Inceptionet blocks are frozen during training so that the parameters for those layers do not change, the last block is made trainable, and a fully connected layer is implemented for a simple MNIST purpose. Ther MNIST has 5 classes and looks into classification of the types of diseases in a certain plant, the dataset is downloaded from Kaggle using opendatasets.
Aux outputs from Inceptionet are voided for this particular model.

The best accuracy for this particular CNN was between 75-80%, I would like to save the parameters of the model for every epoch in training where the validation accuracy is better than the current saved model, and load those parameters for testing purposes allowing the best version of the model being saved. Since this is my first model using pytorch I will be looking into such things later.
