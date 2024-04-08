# CNN-using-transfer-learning

This model implements the Inceptionet model that was originally created by Google for use in GoogLeNet. This is the backbone for the entire model, the first few Inceptionet blocks are frozen during training so that the parameters for those layers do not change, the last block is made trainable, and a fully connected layer is implemented for a simple MNIST problem
