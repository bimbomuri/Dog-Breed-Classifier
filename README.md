# Dog Breed Classifier #

This project is a data capstone project for Udacity Data Science NanoDegree and I am to:

Build a pipeline to process real-world, user-supplied images.
Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human face, the code will identify the resembling dog breed.

Detect Humans
Assess the Human Face Detector The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.

Detect Dogs
Use a pre-trained VGG16 Net to find the predicted class for a given image: dog_detector function returns True if a dog is detected in an image and False if not.

Assess the Dog Detector The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.

CNN to Classify Dog Breeds from Scratch
CNN architecture of trained model attains at least 7% accuracy on the test set.

CNN to Classify Dog Breeds Using Transfer Learning

I used Resnet50 pre-trained for dog detection and if found then used our version Resnet50 trained model to identify the breed.
I used face detector to detect human face if found then used our version of Resnet50 to identity the resembling breed.
The output is much better than I expected. it gives the same breed type to a human who looks the same. even it gives the correct breed of dog in a picture where human was with her.
Model architecture that uses part of a pre-trained model with accuracy on the test set of 80%.

The blogpost can be found on : https://medium.com/@abimbolamuritala65/dog-breed-classifier-dsnd-capstone-project-f798d0f9836
