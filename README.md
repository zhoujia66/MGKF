The file of MGKF_code.zip is the R code corresponding to the method of Multiple Graphical Knockoff Filter introduced in the paper "Reproducible Learning in Large-scale Multiple Graphical Models".
In the file of MGKF_code.zip, RE3.R RE5.R, RE7.R, and RE9.R are the main functions about four examples corresponding to the different settings of Simulation Study 1 in the above-mentioned paper. The remaining files are some auxiliary functions. 
Note that in our simulation, we mainly adopt ISEE to estimate the precision matrices. The isee_all.R includes all the R functions for implementing the innovated scalable efficient estimation (ISEE) procedure introduced in Fan and Lv (2016), written by Fan and Lv.
These two files of slasso.dll and slasso.so are needed to apply ISEE procedure. 

The file of HGKF.zip includes all the R functions for implementing the High-dimensional graphical knockoff filter introduced by Zhou et al.(2022) under the heterogeneous settings.  The R code for appling HGKF are building upon on the code of GGMknockofffilter_R_master wirrten by Li and Maathusis (2021) (https://github.com/Jinzhou-Li/GGMKnockoffFilter-R). Thanks for their sharing. 
