## hookean-springs-pytorch

Hookean springs in PyTorch.

![](media/compgraph.gif)

The main implementation is in `hookean_spring_potential.py` which computes the potential energy of a spring. 

This is demo code for https://medium.com/@juniorrojas/physics-based-simulation-via-backpropagation-on-energy-functions-6d3b0e93f5fb.

## examples

A minimization loop that prints the state after every optimization step. The state is `x`, a `float(n, 2)` tensor where `n` is the number of vertices:

```
python examples/example_no_render.py
```

A basic visualization using matplotlib:

```
python examples/example_render.py
```

![](media/matplotlib.gif)