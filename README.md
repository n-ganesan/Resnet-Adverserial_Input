# Resnet-Adverserial_Input

An Example of how carefully engineered adverserial input can break CNNs

This example creates a CNN based classifcation model on Kaggle's Dogs vs Cats example with RESNET as the underlying classification CNN model.

The training is stopped when the model achieves an accuracy of about 80%. 

The adverserial noise is then added to images of dogs and cats which makes the model misclassify the images which were classified accurately earlier.
