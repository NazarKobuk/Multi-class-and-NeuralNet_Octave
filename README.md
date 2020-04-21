## Multi-class Classification and Neural Networks

## Machine Learning

## Introduction
In this exercise, you will implement one-vs-all logistic regression and neural
networks to recognize hand-written digits. Before starting the programming
exercise, we strongly recommend watching the video lectures and completing
the review questions for the associated topics.
To get started with the exercise, you will need to download the starter
code and unzip its contents to the directory where you wish to complete the
exercise. If needed, use the cd command in Octave/MATLAB to change to
this directory before starting this exercise.
You can also find instructions for installing Octave/MATLAB in the “Environment Setup Instructions” of the course website.
## Files included in this exercise
	ex3.m - Octave/MATLAB script that steps you through part 1
	ex3 nn.m - Octave/MATLAB script that steps you through part 2
	ex3data1.mat - Training set of hand-written digits
	ex3weights.mat - Initial weights for the neural network exercise
	submit.m - Submission script that sends your solutions to our servers
	displayData.m - Function to help visualize the dataset
	fmincg.m - Function minimization routine (similar to fminunc)
	sigmoid.m - Sigmoid function
	lrCostFunction.m - Logistic regression cost function
	oneVsAll.m - Train a one-vs-all multi-class classifier
	predictOneVsAll.m - Predict using a one-vs-all multi-class classifier
	predict.m - Neural network prediction function



## Multi-class Classification
For this exercise, you will use logistic regression and neural networks to
recognize handwritten digits (from 0 to 9). Automated handwritten digit
recognition is widely used today - from recognizing zip codes (postal codes)
on mail envelopes to recognizing amounts written on bank checks. This
exercise will show you how the methods you’ve learned can be used for this
classification task.
In the first part of the exercise, you will extend your previous implemention of logistic regression and apply it to one-vs-all classification

