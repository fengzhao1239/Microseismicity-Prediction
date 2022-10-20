# Microseismicity-Prediction
Microseismicity events happen during the process of hydraulic fracturing and are used to interprete the dimension and direction of the hydaulic fractures. For more information about the usage of microseismicity interpretation, one can refer to [Maxwell (2010)](https://library.seg.org/doi/abs/10.1190/1.3477966).

Dataset includes the microseismicity data (3D coordinates (*x*, *y*, *z*), time, magnitude, calculated distance from the well) and the 5 industrial records (surface pressure, injection rate, proppant concentration, toal concentration volume, toal injection fluid volume).

We want to use the **recorded industrial parameters** to predict the **triggering front** (i.e. the farthest distance of the microseisimity at time *t*).
Our work is similar to [Andrade (2021)](https://library.seg.org/doi/abs/10.1190/geo2021-0094.1). The difference is we want to apply LSTM to predict this time-series problem.

The main procedure to solve this problem is listed as follows:
> 1. Data preparation: 
> 2. 
