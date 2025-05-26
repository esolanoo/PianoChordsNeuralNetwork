# PianoChordsNeuralNetwork
DAQ fed Labview code that categorizes 37 notes and chords of a single DIY piano chord through a Neural Network.

This codes implements a robust Neural network with 12 inputs (1 per note), 3 hidden networks with any number of nodes and a single output classifying the combination of notes and giving the confidence level of the prediction.
It aquires data from a NI DAQ card and processes it through the neural network and a (neatly-made) GUI. It includes a Perceptron algorithm to train the network and store the wights and biases in excel sheets.
This code is capable (with the appropiate time and machine processing capabilities) to correctly predict all possible chords of an octave.

Personal note: This was my final proyect before graduating as a Mechatronics Engineer. I am very proud of this proyect since I overachieved every expectation. The teacher even offered me a job. Some parts may be in spanish (sorry), and here is a link to the video of my presentation (also in spanish): https://drive.google.com/file/d/1feHNpGhdqBhugBO3NQFn3jxtIALqGpS4/view?usp=sharing
