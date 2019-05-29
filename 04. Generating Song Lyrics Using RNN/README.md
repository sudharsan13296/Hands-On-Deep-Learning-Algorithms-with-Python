

# [Chapter 4. Generating Song lyrics with RNN](#)


* [4.1. Hola Recurrent Neural Networks](#)
	* 4.1. The difference between feedforward networks and RNN
* 4.2. Forward Propagation in RNN 
* 4.3. Backpropagation through time (BPTT) 
* 4.4. Deriving BPTT step by step
	* 4.4.1. Gradients with respect to hidden to output layer weights, V
	* 4.4.2. Gradients with respect to hidden to hidden layer weights, W
	* 4.4.3. Gradients with respect to input to hidden layer weights, U
* 4.5. Vanishing and Exploding Gradients
	* 4.5.1. Vanishing Gradients
	* 4.5.2. Exploding Gradients
* [4.6. Generating song lyrics using RNN](#)
* 4.7. Different types of RNN architectures
	* 4.7.1. One-to-One Architecture
	* 4.7.2. One-to-Many Architecture
	* 4.7.3. Many-to-One Architecture
	* 4.7.4. Many-to-Many Architecture