Chebyshev Interpolation and Low rank approximation
=======================
Chebyshev interpolation in 1D and 2D. Interpolates a function and also obtains low-rank decompostion of the matrix from the kernel, K(x_1, x_2). The kernel or the function needs to be added to the corresponding .hpp or .cpp file. No external linear algebra package is needed. However, to compute the error, the example files "Test_Chebyshev_1D" and "Test_Chebyshev_2D" make use of Eigen.