# Memristor learning model
Building memristor model and simulate learning circuit by python.
Inspired by the Spike learning method using STDP(Spike-Time dependency plasticity) material, which is memristor.

### Goal
In this github, we aimed to build a learning model to classify MNIST dataset by using Memristor model.
By composing memristors to a crossbar architecture, It is actually similar to the layer of Artificial Neural Network.

### SADP (with a reverse circuit)
Since memristance variation changes by the amplitude of input-spike,
model could learn things by using SADP(Spike-Amplitude dependency plasticity).
Besides, by simply adding a reverse-input memristor crossbar, the stability of the output got better.  

### Output
Tried out single epoch with 20000 MNIST data, 
and got about 50~60% accuracy.


