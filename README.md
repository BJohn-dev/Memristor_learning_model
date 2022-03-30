# Memristor learning model
Built memristor model and simulated learning circuit with python.
Inspired by Spike learning method using STDP(Spike-Time dependency plasticity) material, which is called memristor.

### Goal
In this repository, we aimed to build a model to classify MNIST dataset by using Memristor grid model.
Composing memristors into a crossbar architecture, It is actually similar to the layer used in Artificial Neural Network.

### SADP (with a reverse circuit)
Since memristance changes according to the amplitude of input-spike,
model could learn things by using SADP(Spike-Amplitude dependency plasticity).
Besides, by simply adding a reverse-input memristor crossbar, we achieved certain stability of the output.  

### Output
Tried out single epoch with 20000 MNIST data, 
and got about 50~60% accuracy.

### Memristance(conductivity) distribution after learning process
![alt Memristance distribution after learning process](https://raw.githubusercontent.com/flninja12/Memristor_learning_model/master/image.png)
