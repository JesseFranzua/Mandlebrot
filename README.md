# Mandlebrot

mandelbrot_code_with_comments.ipynb gives an estimation for the area of the Mandelbrot set using four different random number generation methods.

The variables under the comment # settings allow the user to specify the range of samples and iterations used during the calculation. 

The settings at present lead to a runtime of hours. 

For a quick run of the code we recommmend the replacing the current settings with the following:

n_cores = os.cpu_count()

n_runs = 100

min_i = 10

max_i = 100

n_different_i = 15

min_s = 1000

max_s = 5000

n_different_s = 15



Mandelbrot_picture.ipynb produces an image of the Mandelbrot set. 
