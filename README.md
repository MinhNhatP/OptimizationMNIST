# Optimization in Deep Learning: MOMENTUM, DROPOUT, ADAGRAD



MOMENTUM

The ideal learning rate for the Momentum optimizer also depends on the specific problem and dataset being used. However, in general, Momentum can handle
higher learning rates compared to other optimization methods such as SGD (Stochastic Gradient Descent).
Momentum introduces a momentum term that helps accelerate gradient descent in the relevant direction and dampen oscillations. The momentum term is a
hyperparameter that controls the contribution of the past gradients to the current update direction.
A common default value for the momentum term is 0.9. However, the ideal learning rate and momentum value can be determined through experimentation
and hyperparameter tuning.

ADAGRAD

As a starting point, a commonly used default value for the learning rate in AdaGrad is 0.01. However, it's usually recommended to perform a grid search or other
hyperparameter optimization techniques to find the optimal learning rate for the specific problem at hand.

DROPOUT

The Dropout rate is a hyperparameter that determines the probability of dropping out each unit in the network.
A common default value for the Dropout rate is 0.5, which means that 5096 of the units are randomly dropped out during each training iteration. 
However, the ideal dropout rate can depend on the size and complexity of the network, the nature of the dataset and the amount of noise in the data.
![](https://github.com/MinhNhatP/learningAI/blob/main/277357695_527872315340383_4705246432172441577_n.gif)
![](https://github.com/MinhNhatP/learningAI/blob/main/280891883_379073630904723_3190412736959511262_n.gif)
