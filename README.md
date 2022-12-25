# Solving and Analyzing Mandelbrot and Julia sets
**Solving the complex recursive algorithms for a Mandelbrot and Julia Set and plotting them.**


![image](https://user-images.githubusercontent.com/64051575/209221270-38fa2d48-9b1b-453b-83af-848c73cf2854.png)

![image](https://user-images.githubusercontent.com/64051575/209220962-984e276d-7139-469e-8377-c1242424cb5f.png)

This code experiment involves creating and visualizing a modified version of the Mandelbrot set, a well-known mathematical object in the field of complex dynamics. The set is generated using a recursive algorithm of the form $$z = e^z + c$$, where c is a complex number and z starts at 0. The code defines a function, modified_mandelbrot_set(), which takes in a complex number c and returns 1 if the value of z exceeds a threshold A after a certain number of iterations (set to 100 by default). The code also defines a function, modified_mandelbrot_call(), which generates a set of random complex numbers c and calls the modified_mandelbrot_set() function on each of them. The function then plots either a scatter plot or a density plot of the complex numbers for which modified_mandelbrot_set() returns 1. The code also includes a function, using_mpl_scatter_density(), which adds a color gradient to the density plot using the mpl_scatter_density library and the LinearSegmentedColormap class from matplotlib. The code uses the numpy and matplotlib libraries to perform calculations and create the plots.


