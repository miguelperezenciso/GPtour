# GPtour: Genomic Prediction Tour in R
This is a quick, straight to the point tour on how to implement genomic prediction in R using the most popular algorithms (Lasso, Ridge Regression, GBLUP, Single Step, Bayes A,B,C, Multilayer Perceptron, Convolutional Neural Network). We use [Rstudio](https://www.rstudio.com/) and [learnr](https://rstudio.github.io/learnr/) packages, among other tools.

The main code is in [GPtour.Rmd](https://github.com/miguelperezenciso/GPtour/blob/main/inst/tutorials/tour/GPtour.Rmd) 

## Requirements

You need to install these packages to be able to run [GPtour.Rmd](https://github.com/miguelperezenciso/GPtour/blob/main/inst/tutorials/tour/GPtour.Rmd)

``` r
install.packages("BGLR",repos="https://cran.r-project.org/")  
install.packages("glmnet",repos="https://cran.r-project.org/")  
install.packages("AGHmatrix", repos="https://cran.r-project.org/")  
install.packages('learnr',repos="https://cran.r-project.org/")  
install.packages('downloadthis',repos="https://cran.r-project.org/")  
install.packages("remotes",repos="https://cran.r-project.org/")  
remotes::install_github("rstudio/gradethis") 
``` 
On top, for running deepl learning you need to install miniconda, follow instructions in https://keras.rstudio.com/ 

## How to use

### only once

``` 
install.packages('remotes')
remotes::install_github('miguelperezenciso/GPtour')
```

### to run
```
# type in your console in Rstudio or regular R terminal
library(GPtour)
library(learnr)
learnr::run_tutorial('tour', 'GPtour')
```
You may have an error in mac os if running from terminal. Type this

```
export RSTUDIO_PANDOC=/Applications/RStudio.app/Contents/MacOS/pandoc
```

### Enjoy!
