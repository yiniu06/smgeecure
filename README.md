# smgeecure
This is an R package for fitting marginal semiparametric mixture cure models for clustered survival data.
- Two semiparametric mixture cure models are implemented: the *marginal accelerated failure time mixture cure* (**AFTMC**) model and the *marginal proportional hazards mixture cure* (**PHMC**) model.
- Installation can be done locally after downloading the package manually from this github website. We have also uploaded this package to the Comprehensive R Archive Network (CRAN) at \url{https://cran.r-project.org} so that it can be downloaded as a standard R package using R command  **install.packages("smgeecure")**.

## Package description and included main functions

Our provided main functions are (we refer to their help pages for more details):
- **smgeecure**: fit the models in various ways with syntax
```R
SMC.AuxSP(formula, cureform, sdata, aux = NULL, hetero = FALSE, N = Inf, latency = "PH", nboot = 400)
```
- **print.smgeecure**: print outputted results from SMC.AuxSP() with syntax
```R
print.SMC.AuxSP(object)
```

## Numerical illustrations

### An example using a real dataset from TCGA program is shown below:
```R
library(smgeecure)

```

More practical examples are presented in the help file of *smgeecure()*.

