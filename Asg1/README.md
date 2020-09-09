This repository contains solutions to Assignment 1, the instructions to which are listed in instructions.txt

In Multi_Instance_Learning.ipynb, we train a ResNet classifier for 10 categories of animals. Next we bucket the test input into bags which contain up to 7 random animal pictures. If one of those animals is a dog, the bag is labeled 1. If a bag contains no dog pictures, the bag is labeled 0. We use our pre-trained ResNet classifier to classify whether a bag contains a dog.

In Semi-Supervised_Learning.ipynb, we take a standard breast cancer dataset from scikit learn, and split it 3 ways (33% labeled, 33% unlabeled, 33% test). Next, we train LogR, Label Propagation and Label Spreading algorithms and use them to label unlabelled data. Please read the comments within the colab for greater details.
