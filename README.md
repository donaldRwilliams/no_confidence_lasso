# Reproduce

This repo contains code to reproduce the simulations: 

1. download the repo as a .zip file (click green button)

2. set the folder `reproduce` as the working directory


## File Descriptions

* `regression.Rmd`: Multiple regression experiments
* `network.Rmd`: Partial correlation network experiments
* `why_it_matters.Rmd`: Illustration of l1 sampling distribution in introduction

## Note
I used the package **GGMncv** to bootstrap the L1-regularized relations. In practice,
**bootnet** is used in the network literature. The one difference is that **GGMncv**
penalizes the diagonal, whereas **bootnet** does not. The results do not depend on this
minor difference. 

The `.Rda` files are the simulation results that were presented
in the paper.