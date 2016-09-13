# pss
R package to perform bounds test for cointegration and perform dynamic simulations.

## Details
`pss` is an R package to perform the Pesaran, Shin, and Smith (2001) bounds test for cointegration and perform dynamic simulations of the resulting output.

Currently, only the bounds test function is operational (`pssbounds`); the dynamic function (`dynpss`) is still under development, and not yet available. For details on each of these programs, see http://andyphilips.github.io/pssbounds/ and http://andyphilips.github.io/dynpss/, respectively

:warning: This package is under development. If any bugs are found, please direct them to the authors.

## Download
To download `pss`, you will need to obtain the `devtools` package and make a call from R to GitHub:
```r
install.packages("devtools")
library(devtools)
install_github("andyphilips/pss")
library(pss)
```
You should now be ready to use `pss`.

## Authors
Soren Jordan, Department of Political Science, Auburn University. sorenjordanpols@gmail.com. http://sorenjordan.com

Andrew Q Philips, Department of Political Science, Texas A&M University. aphilips@pols.tamu.edu. http://people.tamu.edu/~aphilips/. @andyphilips.

## Citation
If you use `pss`, please cite:

Jordan, Soren and Andrew Q. Philips. "pss: R package to perform the bounds test for cointegration and perform dynamic simulations."

and

Philips, Andrew Q. "Have your cake and eat it too? Cointegration and dynamic inference from autoregressive distributed lag models" Working Paper.

## References
Pesaran, M Hashem, Yongcheol Shin and Richard J Smith. 2001. "Bounds testing approaches to the analysis of level relationships." Journal of Applied Econometrics 16(3):289-326.

## Version
0.1.3.9000
