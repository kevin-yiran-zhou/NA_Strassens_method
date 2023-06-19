# Final Project: MA-UY 4424 Numerical Analysis

Strassen’s method is an algorithm for large matrix multiplication. It is faster than the normal matrix multiplication algorithm.

The main idea of this project is to research Strassen’s method and implement the algorithm. First, we did a run-time analysis on both Strassen’s method and the normal method. Then, we implemented the algorithms with a Python program. We timed how long a matrix multiplication takes using both Strassen’s method and the normal method. We tried matrices of different sizes, from (2, 2) to (4096, 4096). We plotted the results in the same plot and compared them. We compared the results of the run-time analysis and the Python program to verify that Starssen’s method can be faster than the normal method of matrix multiplication for large matrices.

Additionally, we tried to combine Strassen’s method and the normal method for matrix multiplication. We set the size of matrices at the base step of Strassen’s method to (2, 2), (4, 4), or (8, 8). With this improvement, we accomplished a revised Strassen’s method which is much faster than the basic Strassen’s method.
