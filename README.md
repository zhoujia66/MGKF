This is R code corresponding to the method of Multiple Graphical Knockoff Filter introduced in the paper "Reproducible Learning in Large-scale Multiple Graphical Models".
In this file, RE3.R RE5.R, RE7.R, and RE9.R are the main functions and four examples corresponding to the different settings of Simulation Study 1 in the above-mentioned paper. The remaining files are some auxiliary functions. 
Note that in our simulation, we mainly adopt ISEE to estimate the precision matrices. The isee_all.R is used to apply this procedure, written by Fan and Lv. It includes all the R functions for implementing the innovated scalable efficient estimation (ISEE) procedure introduced in Fan and Lv (2016).
These two files of slasso.dll and slasso.so are used to apply ISEE procedure. 
