# Fractal_Dimenions_Logistic_Curve_Fitting_via_Optimization_L-BFGS-B_Method_R_code
Logistic Curve Fitting for Fractal Dimension growth via Optimization - L-BFGS-B Method - R-code


The code fits a logistic growth model to the observed values of the fractal dimension of a urban areas over time. The logistic growth model is a function that has two parameters: the carrying capacity of the fractal dimension, denoted by `x[1]`, which is the maximal fractal dimension, and the growth rate of the fractal dimension, denoted by `x[2]`. The code first defines the logistic growth model function, then defines the sum of least squares function, and finally uses the `optim()` function, of the  L-BFGS-B method, to minimize the sum of least squares function. The code then prints the results of the optimization, including the values of the parameters, the value of the function at the minimum, and the number of iterations. The code can be used to study the growth of the fractal dimension of a city over time, predict the future fractal dimension of a city, or analyze the impact of a new urban planning policy on the growth of the fractal dimension of a city.

In the code, the following variables are used:

* `y`: The observed values of the fractal dimension of the city at different time points.
* `t`: The time points at which the observed values of the fractal dimension were collected.
* `x`: The parameters of the logistic growth model.
* `t[1]`: The initial studied year.

The provided values of observation vectors y and t are just an example and should be changed according to the collected data.
