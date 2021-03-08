# FSDL_Labs
This is my personal repo for notes/workbooks from Labs of the UC Berkeley Spring 2021 course: Full Stack Deep Learning. 

The purpose of these labs is to mimic the production and deployment of a ML tool, in this case a paragraph recognition model for handwritten text.

https://fullstackdeeplearning.com/spring2021/

All labs were run through Google Collab.

# Contents
## Coding a neural network from scratch
Coding basic gradient descent back-propogation for 2-dimensional data from scratch, with Tensorflow/Keras, with PyTorch.

## Lab 1: Setup and Introduction
Formualate a problem & create a structured codebase to address it. Train an MLP on MNIST data.
## Lab 2: CNN's and Synthetic Data
Train CNN's to recognize characters and lines of text, use EMNIST, generate synthetuc handwritten lines to use as data.
## Lab 3: RNNs
Train RNN's for full line text recognition using CNN + LSTM with CTC loss.
## Lab 4: Transformers
Train Transformers for full line text recognition.
## Lab 5: Experiment Management
Looking at real handwriting data, using weights and biases and hyperparameter sweeps to run experiments.
## Lab 6: Line/Paragraph Detection
Train/Evaluate/Implement a full paragraph recognition model.
## Lab 7: Data Management
Label handiwriting data and establish SOP's for data management.
## Lab 8: Continuous Integration
Add continuous linting and testing of the paragraph recognition model.
## Lab 9: Deployment
Run the full model locally as a REST API, then in Docker, then in production using AWS Lambda.
## Lab 10: Monitoring
Set up automated monitoring that will alert to changes in incoming data or prediction distribution changes. 
