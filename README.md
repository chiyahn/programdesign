# programdesign

![Build Status](https://travis-ci.com/chiyahn/programdesign-dev.svg?token=8UzquqsERVnpPhmVsamP&branch=master)
[![codecov](https://codecov.io/gh/chiyahn/programdesign-dev/branch/master/graphs/badge.svg)](https://codecov.io/gh/chiyahn/programdesign-dev)

`programdesign` is an R package for replications for [Optimal transfer program design and counterfactual welfare effects] by Chiyoung Ahn. 

The development version of the package can be found [here](https://github.com/chiyahn/programdesign-dev). Note that permission is required for an access to the repository -- email me at chiyahn@mail.ubc.ca for access.

Installing `programdesign`
------------

Open R console and run the following script.

``` r
# install.packages("devtools") # if devtools has not been installed, run this line.
devtools::install_github("chiyahn/programdesign")
```

Running experiments
------------

Run `experiments/experiments.R` to replicate the Monte-Carlo experiments and generate plots in the paper. This will run `dgp1.R` for DGP 1 and `dgp2.R` for DGP 2 in the simulation section. 

Note that the plots are generated in both TeX `.tex` (using `tikz`) and  `.png` image files. 
