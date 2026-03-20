# Numerical_Analysis_project
in this project, I implemented numerical integration using the trapezium rule in Python. I first defined the integrand function and used a basic routine (trap0) to approximate the integral by dividing the interval into a number of trapeziums. I then increased the number of trapeziums until the result converged to a stable value, allowing me to estimate the integral and determine the number required for a given accuracy.

To improve this, I used an enhanced function (trap1) that automatically adjusts the number of trapeziums. This function repeatedly doubles the number of intervals and compares successive results until a specified relative accuracy is achieved. This removed the need for manual trial and error.

I then applied these methods to more complex integrals, including one with an infinite range (handled by truncation) and a physical example involving a pendulum, where I had to analyse and fix issues with divergence by changing variables. Finally, I explored more efficient numerical integration using SciPy and compared it to my own implementation.
