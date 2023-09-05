# (Geo)spatial Statistics with R (Meuse)

Welcome to this (Geo)spatial Statistics with R Assignment!

In this exercise, we will explore the concepts and applications of Deterministic and Stochastic Interpolation Methods. We traverse such technics as:

&nbsp;&nbsp;&nbsp;**1) Deterministic methods**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Thiessen polygons  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. Inverse Distance Weighting  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. Linear Regression  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Ordinary Least Squares  
&nbsp;&nbsp;&nbsp;**2) Stochastic methods**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Variograms and Kriging  
&nbsp;&nbsp;&nbsp;**3)** we also briefly highlight ways we can **assess the quality** of an interpolation  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Cross-validation; and end with  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. Residual Mean Squared Error (rmse).

For these set of exersices we use a dataset that is well-suited to illustrate these concepts. The [meuse](https://search.r-project.org/CRAN/refmans/sp/html/meuse.html) data set which comes with the `gstat` package. 
**meuse**: gives locations (on a regular grid) and topsoil heavy metal concentrations, along with a number of soil and landscape variables at the observation locations, collected in a flood plain of the river Meuse, near the village of Stein (NL). Heavy metal concentrations are from composite samples of an area of approximately 15 m x 15 m.
