# instats-ModernDive

Materials for the course "Statistics in R with Tidyverse" for Instats by 
Dr. Chester Ismay following <https://moderndive.com/v2/>

To get going make sure to install the following R packages first:

```r
packages <- c("dplyr", "fivethirtyeight", "ggplot2", "knitr", "lubridate",
                    "moderndive", "palmerpenguins", "readr", "rmarkdown",
                    "tibble", "tidyr", "GGally")

install.packages(packages, repos = "https://cran.rstudio.com")
```

If you'd like a bit of a shortcut but can be a little tricky to install on
different operating systems, you can install the very large `tidyverse` package
instead for some of the packages above:

```r
packages_revised <- c("fivethirtyeight", "knitr", "moderndive", "palmerpenguins",
                      "rmarkdown", "GGally", "tidyverse")

install.packages(packages_revised, repos = "https://cran.rstudio.com")
```
