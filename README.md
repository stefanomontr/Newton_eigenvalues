# Newton_eigenvalues
Notes on implementation of a function that uses Newton method to find eigenvalues of a matrix.

char_coeff() calculates coefficients of characteristic polynomial of matrix

char_polynomial() x and y values of characteristic polynomial

newton_eig() approximates one eigenvalue (i.e. one solution of characteristic polynomial) from an initial guess

all_newton() calls newton_eig() passing as initial guesses all values where characteristic polynomial changes its sign (from positive to negative or vice versa)
