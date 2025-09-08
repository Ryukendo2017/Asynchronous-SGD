# Asynchronous-SGD
## Convergence Guarantees for Asynchronous Stochastic Gradient Descent in Continuous Time

### sgd_sim_synthetic.ipynb

This file contains the necessary codes for simulating A-SGD and obtaining the correspoding upper-bound(s) for a synthetic objective function:
$$
f(\theta) = \theta^\top Q\theta + \epsilon\sin(w^\top\theta)
$$

The parameters are kept exactly the same as the paper.

### sgd_sim_nn.ipynb

This file contains the necessary codes for simulating A-SGD and obtaining upper-bound(s) for a VGG16 network on CIFAR100 dataset. The parameters are keps exactly the same as in the paper. Plots might vary due to multiple re-runs.
