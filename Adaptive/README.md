# Adaptive

Jupyter Notebooks in this folder are for the numerical example in section 4.4

1. Activation functions: Leaky ReLU

2. Parameter h is the size of quadrature points in the domian. In this example the domain is [0,1], hence 1/h is the number of quadrature points for uniform partition.

3. poisson_FOSLS_adaptive_leaky_relu.ipynb is for adaptive refinement in section 4.4. poisson_equation_leaky_uniform_200pts is the model after 2000 iterations' training on 200 uniform quadrature points. As in the notebook, load the file as the start for adaptive refinement procedure.

4. Poisson_FOSLS_Uniform_LeakyRelu.ipynb is for uniform refinement. Change h to get different uniform partition size.
