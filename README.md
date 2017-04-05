Computational Physics Assignment #5

Problem #1 - Data Fitting.

 In this problem we are given a set of data which gives the temperature in Munich every day for several years; we mask the bad values and then try and fit a given function to the data; from there we are asked to make a plot of the data and best-fit model for a certain time range. We are also asked to give (a) the best-fit values of the parameters, (b) the overall average temperature, and the typical daily average values predicted by the model for the coldest and hottest time of the year, as well as give (c) the meaning of the 'b' parameter.  
 
 The answers are as follows:
  (a) The best-fit values for the parameters are as follows: a =  14.0 , b =  2.942 , and c =  9.4403
      The plot of the data and fitted model is shown separately
  (b) The overall average temperature of Munich is:  9.4403 degrees Celsius
      According to the model, the hottest temperature is:  23.4402 degrees Celsius
      According to the model, the coldest temperature is:  -4.5594 degrees Celsius
  (c) The meaning of the b parameter is the left-right shift of the cosine function.
      The value does make sense, because without it the cosine term will be at its maximum
      value at the beginning of the year according to the model, which we know is incorrect

 The graph is included in the repository and is titled 'Munich.eps'. 
 
Problem #2 - SDSS Data Fitting.

 After downloading data from the SDSS DR13 data, we are asked to make certain selections within the fits file data and fit three different functions: linear, quadratic fit, and broken linear (two connected linear fits). Then we are asked for the (a) best-fit values of the parameters and to tell (b) which function fits the data best. 
 
 The answers are as follows:
 (a) Linear Best-Fit Values: Slope: 5.063, Intercept: 17.453. Quadratic Best-Fit Values: a: -2.175, b: 6.802, c: 17.305.
    
 (b) The broken linear is the best fit; I can't really tell where it is 'broken' because it looks like just a straight line, but whatevs. The data doesn't look super linear according to the blue colored data; the linear function is definitely not right and the quadratic function is arguably just as bad, if not worse of a fit. We would expect the broken linear function to fit the data best.

 The graph is included in the repository and is titled 'SDSS.eps'.
