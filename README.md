## SpykeTorch could reach 96.89% acc on MNIST. 

This is a good attempt on the training of SNN with pure STDP, even though there is still a trick on the weights search tuning. However, the constructed convolutional layer in this paper may the main contribution to the accuracy which is also usually considered powerful on the featuer detection in ANNs. (thomas)

Original introduction about the app is listed here: 
High-speed simulator of convolutional spiking neural networks with at most one spike per neuron.
SpykeTorch is a PyTorch-based simulator of convolutional spiking neural networks, in which the neurons emit at most one spike per stimulus. SpykeTorch supports STDP and Reward-modulated STDP learning rules. The current code is the early object oriented version of this simulator and you can find the documentation in docs folder in PDF format or in our lab website (http://cnrl.ut.ac.ir/SpykeTorch/doc/) in HTML format. Since SpykeTorch is fully compatible with PyTorch, you can easily use it if you know PyTorch. A tutorial is available in the preprint titled "SpykeTorch: Efficient Simulation of Convolutional Spiking Neural Networks with at most one Spike per Neuron" which introduces the SpykeTorch package (https://arxiv.org/abs/1903.02440).
MozafariShallow.py is the reimplementation of the paper "First-Spike-Based Visual Categorization Using Reward-Modulated STDP" (https://ieeexplore.ieee.org/document/8356226/), and MozafariDeep.py is the reimplementation of the paper "Bio-Inspired Digit Recognition Using Spike-Timing-Dependent Plasticity (STDP) and Reward-Modulated STDP in Deep Convolutional Networks" (https://arxiv.org/abs/1804.00227), using SpykeTorch.

