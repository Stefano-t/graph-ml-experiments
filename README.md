# Graph Machine Learning Practice

Experiments with various graph machine learning algorithms, both implemented from scratch and using external libraries.

## Required dependencies

To run most of the code, you will need (without any particular version):

- [pytorch](https://pytorch.org/)
- [networkx](https://networkx.org/)
- [pytorch geometric](https://pytorch-geometric.readthedocs.io/en/latest/index.html)
- pandas and numpy, of course ;)

## Dataset

This repo also contains some external toy dataset, and they're all taken from this beautiful site: [Network Data Repository](https://networkrepository.com/). You can find lots of networks, and it helps you visualize and explore some relevant information (such as sparsity, heterogeneity etc.) before downloading it.

## About the code

I tried to implement basic staff from scratch, to better understand what was going on. It isn't (and surely doesn't pretend to be) the most efficient and bug-free code you'll ever see, but it might help you grasping the concept behind some theory. Unfortunately, the graph neural network stuff is only implement through pytorch geometric, since creating from scratch a sparse and scalable neural network is quite complex, and I haven't all the time of the world :_(.
