Overview
This artifact is a short slide deck where I walk through the basic architecture of a neural network using visuals instead of equations. The goal is to show how data moves from the input layer, through hidden layers, to the output layer and how each piece (neurons, weights, activations, loss, optimizer) works together during training.

How I Built It
I sketched the architecture based on how I usually picture models when debugging them at work. I used my experiments in the Neural Network Playground (changing layers, neurons, learning rate and noise) to ground the explanations in concrete behavior I’ve actually seen instead of just theory.

What I Learned
Putting this together helped me connect the math to an intuitive mental model:
More layers and neurons give the network room to learn richer patterns, but also make it easier to overfit.
Activation functions are the key to moving beyond straight-line decision boundaries.
