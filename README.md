# decay_pc_demo
Demonstrates the generative properties of predictive coding networks when using weight decay and value=node decay. It implements the methods published in the paper

> W Sun, J Orchard, “[A Predictive-Coding Network That Is Both Discriminative and Generative](https://www.mitpressjournals.org/doi/abs/10.1162/neco_a_01311), *Neural Computation*, 32(10):1836-1862, October 2020. ([pdf](http://www.cs.uwaterloo.ca/~jorchard/academic/SunOrchard_NECO2020.pdf))

This code uses PyTorch.

To try it, just `git clone` the repository and run the `runme` notebooks.

If you want to try the MNIST demo (`runme_MNIST`), then you'll need to also get the MNIST dataset. There are various ways to do that, but if you want to use this code as-is (without having to massage the MNIST data), you can download `mnist.pkl` from my Dropbox [here](https://www.dropbox.com/s/fi8x5p24p3z0m6z/mnist.pkl?dl=0) (220MB).

