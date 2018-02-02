Metworx v 3.0.2-r2 R packages
================

R package compatibility wtih Metworx 3.0.2-r2
=============================================

Please refer to this listing when having R package installation problems.

The following list of packages were installed to a temporary location on the Metworx 3.0.2-r2 AMI as part of the validation process. These packages (at the indicated version) are *not still located on the AMI*, but are/were installable via CRAN. Newer versions of these packages may install without issue, but the versions listed should *always* be able to be installed on the indicated version of the AMI.

If you have additional R packages you'd like to have validated for installation upon the next AMI release, please open an issue in the [GitHub issue tracker](https://github.com/metrumresearchgroup/metworx-listings/issues) and let us know which ones you'd like added.

Listing of versions
===================

``` r
kable(installed.packages(validation_lib)[,c("Package","Version","Built","LibPath")], row.names = FALSE)
```

| Package        | Version     | Built | LibPath              |
|:---------------|:------------|:------|:---------------------|
| acepack        | 1.4.1       | 3.3.3 | /data/validation-lib |
| akima          | 0.6-2       | 3.3.3 | /data/validation-lib |
| arm            | 1.9-3       | 3.3.3 | /data/validation-lib |
| ash            | 1.0-15      | 3.3.3 | /data/validation-lib |
| assertthat     | 0.2.0       | 3.3.3 | /data/validation-lib |
| backports      | 1.1.2       | 3.3.3 | /data/validation-lib |
| BB             | 2014.10-1   | 3.3.3 | /data/validation-lib |
| bdsmatrix      | 1.3-3       | 3.3.3 | /data/validation-lib |
| bindr          | 0.1         | 3.3.3 | /data/validation-lib |
| bindrcpp       | 0.2         | 3.3.3 | /data/validation-lib |
| bit            | 1.1-12      | 3.3.3 | /data/validation-lib |
| bit64          | 0.9-7       | 3.3.3 | /data/validation-lib |
| blob           | 1.1.0       | 3.3.3 | /data/validation-lib |
| brew           | 1.0-6       | 3.3.3 | /data/validation-lib |
| broom          | 0.4.3       | 3.3.3 | /data/validation-lib |
| bvpSolve       | 1.3.3       | 3.3.3 | /data/validation-lib |
| callr          | 2.0.1       | 3.3.3 | /data/validation-lib |
| car            | 2.1-6       | 3.3.3 | /data/validation-lib |
| caret          | 6.0-78      | 3.3.3 | /data/validation-lib |
| cellranger     | 1.1.0       | 3.3.3 | /data/validation-lib |
| checkmate      | 1.8.5       | 3.3.3 | /data/validation-lib |
| cli            | 1.0.0       | 3.3.3 | /data/validation-lib |
| clisymbols     | 1.2.0       | 3.3.3 | /data/validation-lib |
| covr           | 3.0.1       | 3.3.3 | /data/validation-lib |
| crayon         | 1.3.4       | 3.3.3 | /data/validation-lib |
| crosstalk      | 1.0.0       | 3.3.3 | /data/validation-lib |
| CVST           | 0.2-1       | 3.3.3 | /data/validation-lib |
| data.table     | 1.10.4-3    | 3.3.3 | /data/validation-lib |
| DBI            | 0.7         | 3.3.3 | /data/validation-lib |
| dbplyr         | 1.2.0       | 3.3.3 | /data/validation-lib |
| ddalpha        | 1.3.1       | 3.3.3 | /data/validation-lib |
| debugme        | 1.1.0       | 3.3.3 | /data/validation-lib |
| DEoptimR       | 1.0-8       | 3.3.3 | /data/validation-lib |
| deSolve        | 1.20        | 3.3.3 | /data/validation-lib |
| dfoptim        | 2017.12-1   | 3.3.3 | /data/validation-lib |
| dimRed         | 0.1.0       | 3.3.3 | /data/validation-lib |
| DoseFinding    | 0.9-16      | 3.3.3 | /data/validation-lib |
| dparser        | 0.1.8       | 3.3.3 | /data/validation-lib |
| dplyr          | 0.7.4       | 3.3.3 | /data/validation-lib |
| DRR            | 0.0.3       | 3.3.3 | /data/validation-lib |
| expm           | 0.999-2     | 3.3.3 | /data/validation-lib |
| extrafont      | 0.17        | 3.3.3 | /data/validation-lib |
| extrafontdb    | 1.0         | 3.3.3 | /data/validation-lib |
| fastmatch      | 1.1-0       | 3.3.3 | /data/validation-lib |
| fda            | 2.4.7       | 3.3.3 | /data/validation-lib |
| flexsurv       | 1.1         | 3.3.3 | /data/validation-lib |
| forcats        | 0.2.0       | 3.3.3 | /data/validation-lib |
| Formula        | 1.2-2       | 3.3.3 | /data/validation-lib |
| gam            | 1.14-4      | 3.3.3 | /data/validation-lib |
| gamlss         | 5.0-6       | 3.3.3 | /data/validation-lib |
| gamlss.data    | 5.0-0       | 3.3.3 | /data/validation-lib |
| gamlss.dist    | 5.0-4       | 3.3.3 | /data/validation-lib |
| gamm4          | 0.2-5       | 3.3.3 | /data/validation-lib |
| gapminder      | 0.3.0       | 3.3.3 | /data/validation-lib |
| gdata          | 2.18.0      | 3.3.3 | /data/validation-lib |
| geosphere      | 1.5-7       | 3.3.3 | /data/validation-lib |
| ggalt          | 0.4.0       | 3.3.3 | /data/validation-lib |
| ggmap          | 2.6.1       | 3.3.3 | /data/validation-lib |
| ggplot2        | 2.2.1       | 3.3.3 | /data/validation-lib |
| ggthemes       | 3.4.0       | 3.3.3 | /data/validation-lib |
| glue           | 1.2.0       | 3.3.3 | /data/validation-lib |
| gmp            | 0.5-13.1    | 3.3.3 | /data/validation-lib |
| gower          | 0.1.2       | 3.3.3 | /data/validation-lib |
| gplots         | 3.0.1       | 3.3.3 | /data/validation-lib |
| gridBase       | 0.4-7       | 3.3.3 | /data/validation-lib |
| gsubfn         | 0.6-6       | 3.3.3 | /data/validation-lib |
| gtools         | 3.5.0       | 3.3.3 | /data/validation-lib |
| haven          | 1.1.1       | 3.3.3 | /data/validation-lib |
| hexbin         | 1.27.2      | 3.3.3 | /data/validation-lib |
| Hmisc          | 4.1-1       | 3.3.3 | /data/validation-lib |
| hms            | 0.4.1       | 3.3.3 | /data/validation-lib |
| HSAUR2         | 1.1-17      | 3.3.3 | /data/validation-lib |
| htmlTable      | 1.11.2      | 3.3.3 | /data/validation-lib |
| htmlwidgets    | 1.0         | 3.3.3 | /data/validation-lib |
| httr           | 1.3.1       | 3.3.3 | /data/validation-lib |
| igraph         | 1.1.2       | 3.3.3 | /data/validation-lib |
| ipred          | 0.9-6       | 3.3.3 | /data/validation-lib |
| irlba          | 2.3.2       | 3.3.3 | /data/validation-lib |
| jpeg           | 0.1-8       | 3.3.3 | /data/validation-lib |
| jsonlite       | 1.5         | 3.3.3 | /data/validation-lib |
| kernlab        | 0.9-25      | 3.3.3 | /data/validation-lib |
| Lahman         | 6.0-0       | 3.3.3 | /data/validation-lib |
| latticeExtra   | 0.6-28      | 3.3.3 | /data/validation-lib |
| lava           | 1.6         | 3.3.3 | /data/validation-lib |
| lazyeval       | 0.2.1       | 3.3.3 | /data/validation-lib |
| lme4           | 1.1-15      | 3.3.3 | /data/validation-lib |
| lmtest         | 0.9-35      | 3.3.3 | /data/validation-lib |
| lubridate      | 1.7.1       | 3.3.3 | /data/validation-lib |
| manipulate     | 1.0.1       | 3.3.3 | /data/validation-lib |
| mapproj        | 1.2-5       | 3.3.3 | /data/validation-lib |
| maps           | 3.2.0       | 3.3.3 | /data/validation-lib |
| MatrixModels   | 0.4-1       | 3.3.3 | /data/validation-lib |
| maxLik         | 1.3-4       | 3.3.3 | /data/validation-lib |
| MEMSS          | 0.9-2       | 3.3.3 | /data/validation-lib |
| microbenchmark | 1.4-4       | 3.3.3 | /data/validation-lib |
| minqa          | 1.2.4       | 3.3.3 | /data/validation-lib |
| miscTools      | 0.6-22      | 3.3.3 | /data/validation-lib |
| mlmRev         | 1.0-6       | 3.3.3 | /data/validation-lib |
| mnormt         | 1.5-5       | 3.3.3 | /data/validation-lib |
| ModelMetrics   | 1.1.0       | 3.3.3 | /data/validation-lib |
| modelr         | 0.1.1       | 3.3.3 | /data/validation-lib |
| msm            | 1.6.5       | 3.3.3 | /data/validation-lib |
| mstate         | 0.2.10      | 3.3.3 | /data/validation-lib |
| muhaz          | 1.2.6       | 3.3.3 | /data/validation-lib |
| mvtnorm        | 1.0-7       | 3.3.3 | /data/validation-lib |
| nloptr         | 1.0.4       | 3.3.3 | /data/validation-lib |
| NMF            | 0.20.6      | 3.3.3 | /data/validation-lib |
| numDeriv       | 2016.8-1    | 3.3.3 | /data/validation-lib |
| nycflights13   | 0.2.2       | 3.3.3 | /data/validation-lib |
| optextras      | 2016-8.8    | 3.3.3 | /data/validation-lib |
| optimx         | 2013.8.7    | 3.3.3 | /data/validation-lib |
| pander         | 0.6.1       | 3.3.3 | /data/validation-lib |
| pbkrtest       | 0.4-7       | 3.3.3 | /data/validation-lib |
| PBSddesolve    | 1.12.2      | 3.3.3 | /data/validation-lib |
| PBSmodelling   | 2.68.6      | 3.3.3 | /data/validation-lib |
| pillar         | 1.1.0       | 3.3.3 | /data/validation-lib |
| pkgconfig      | 2.0.1       | 3.3.3 | /data/validation-lib |
| pkgmaker       | 0.22        | 3.3.3 | /data/validation-lib |
| PKPDmodels     | 0.3.2       | 3.3.3 | /data/validation-lib |
| plm            | 1.6-6       | 3.3.3 | /data/validation-lib |
| plogr          | 0.1-1       | 3.3.3 | /data/validation-lib |
| plotly         | 4.7.1       | 3.3.3 | /data/validation-lib |
| plotrix        | 3.7         | 3.3.3 | /data/validation-lib |
| png            | 0.1-7       | 3.3.3 | /data/validation-lib |
| prodlim        | 1.6.1       | 3.3.3 | /data/validation-lib |
| proj4          | 1.0-8       | 3.3.3 | /data/validation-lib |
| proto          | 1.0.0       | 3.3.3 | /data/validation-lib |
| psych          | 1.7.8       | 3.3.3 | /data/validation-lib |
| purrr          | 0.2.4       | 3.3.3 | /data/validation-lib |
| quadprog       | 1.5-5       | 3.3.3 | /data/validation-lib |
| quantreg       | 5.34        | 3.3.3 | /data/validation-lib |
| R6             | 2.2.2       | 3.3.3 | /data/validation-lib |
| Rcgmin         | 2013-2.21   | 3.3.3 | /data/validation-lib |
| Rcpp           | 0.12.15     | 3.3.3 | /data/validation-lib |
| RcppArmadillo  | 0.8.300.1.0 | 3.3.3 | /data/validation-lib |
| RcppRoll       | 0.2.2       | 3.3.3 | /data/validation-lib |
| readr          | 1.1.1       | 3.3.3 | /data/validation-lib |
| readxl         | 1.0.0       | 3.3.3 | /data/validation-lib |
| recipes        | 0.1.2       | 3.3.3 | /data/validation-lib |
| registry       | 0.5         | 3.3.3 | /data/validation-lib |
| rematch        | 1.0.1       | 3.3.3 | /data/validation-lib |
| reprex         | 0.1.2       | 3.3.3 | /data/validation-lib |
| rex            | 1.1.2       | 3.3.3 | /data/validation-lib |
| RgoogleMaps    | 1.4.1       | 3.3.3 | /data/validation-lib |
| rJava          | 0.9-9       | 3.3.3 | /data/validation-lib |
| rjson          | 0.2.15      | 3.3.3 | /data/validation-lib |
| RJSONIO        | 1.3-0       | 3.3.3 | /data/validation-lib |
| rlang          | 0.1.6       | 3.3.3 | /data/validation-lib |
| R.methodsS3    | 1.7.1       | 3.3.3 | /data/validation-lib |
| rngtools       | 1.2.4       | 3.3.3 | /data/validation-lib |
| robustbase     | 0.92-8      | 3.3.3 | /data/validation-lib |
| ROCR           | 1.0-7       | 3.3.3 | /data/validation-lib |
| R.oo           | 1.21.0      | 3.3.3 | /data/validation-lib |
| rootSolve      | 1.7         | 3.3.3 | /data/validation-lib |
| RSQLite        | 2.0         | 3.3.3 | /data/validation-lib |
| rstudioapi     | 0.7         | 3.3.3 | /data/validation-lib |
| rtf            | 0.4-11      | 3.3.3 | /data/validation-lib |
| Rttf2pt1       | 1.3.5       | 3.3.3 | /data/validation-lib |
| R.utils        | 2.6.0       | 3.3.3 | /data/validation-lib |
| rvest          | 0.3.2       | 3.3.3 | /data/validation-lib |
| Rvmmin         | 2017-7.18   | 3.3.3 | /data/validation-lib |
| RxODE          | 0.6-1       | 3.3.3 | /data/validation-lib |
| sandwich       | 2.4-0       | 3.3.3 | /data/validation-lib |
| sde            | 2.0.15      | 3.3.3 | /data/validation-lib |
| selectr        | 0.3-1       | 3.3.3 | /data/validation-lib |
| sessioninfo    | 1.0.0       | 3.3.3 | /data/validation-lib |
| setRNG         | 2013.9-1    | 3.3.3 | /data/validation-lib |
| sfsmisc        | 1.1-1       | 3.3.3 | /data/validation-lib |
| sp             | 1.2-7       | 3.3.3 | /data/validation-lib |
| SparseM        | 1.77        | 3.3.3 | /data/validation-lib |
| SQUAREM        | 2017.10-1   | 3.3.3 | /data/validation-lib |
| stargazer      | 5.2.1       | 3.3.3 | /data/validation-lib |
| stringr        | 1.2.0       | 3.3.3 | /data/validation-lib |
| svUnit         | 0.7-12      | 3.3.3 | /data/validation-lib |
| tibble         | 1.4.2       | 3.3.3 | /data/validation-lib |
| tidyr          | 0.8.0       | 3.3.3 | /data/validation-lib |
| tidyselect     | 0.2.3       | 3.3.3 | /data/validation-lib |
| tidyverse      | 1.2.1       | 3.3.3 | /data/validation-lib |
| timeDate       | 3042.101    | 3.3.3 | /data/validation-lib |
| tnet           | 3.0.14      | 3.3.3 | /data/validation-lib |
| ucminf         | 1.1-4       | 3.3.3 | /data/validation-lib |
| utf8           | 1.1.3       | 3.3.3 | /data/validation-lib |
| viridis        | 0.4.1       | 3.3.3 | /data/validation-lib |
| viridisLite    | 0.3.0       | 3.3.3 | /data/validation-lib |
| whisker        | 0.3-2       | 3.3.3 | /data/validation-lib |
| withr          | 2.1.1       | 3.3.3 | /data/validation-lib |
| XML            | 3.98-1.9    | 3.3.3 | /data/validation-lib |
| xml2           | 1.2.0       | 3.3.3 | /data/validation-lib |
| xpose4         | 4.6.0       | 3.3.3 | /data/validation-lib |

Session info
============

    ## ─ Session info ──────────────────────────────────────────────────────────
    ##  setting  value                       
    ##  version  R version 3.3.3 (2017-03-06)
    ##  os       Ubuntu 14.04.5 LTS          
    ##  system   x86_64, linux-gnu           
    ##  ui       X11                         
    ##  language (EN)                        
    ##  collate  en_US.UTF-8                 
    ##  tz       Etc/UTC                     
    ##  date     2018-02-02                  
    ## 
    ## ─ Packages ──────────────────────────────────────────────────────────────
    ##  package     * version date       source        
    ##  backports     1.0.4   2016-10-24 CRAN (R 3.3.2)
    ##  clisymbols    1.2.0   2017-05-21 CRAN (R 3.3.3)
    ##  digest        0.6.10  2016-08-02 CRAN (R 3.3.2)
    ##  evaluate      0.10    2016-10-11 CRAN (R 3.3.2)
    ##  highr         0.6     2016-05-09 CRAN (R 3.3.2)
    ##  htmltools     0.3.5   2016-03-21 CRAN (R 3.3.2)
    ##  knitr       * 1.15.1  2016-11-22 CRAN (R 3.3.2)
    ##  magrittr      1.5     2014-11-22 CRAN (R 3.3.2)
    ##  Rcpp          0.12.8  2016-11-17 CRAN (R 3.3.2)
    ##  rmarkdown     1.3     2016-12-21 CRAN (R 3.3.2)
    ##  rprojroot     1.1     2016-10-29 CRAN (R 3.3.2)
    ##  sessioninfo * 1.0.0   2017-06-21 CRAN (R 3.3.3)
    ##  stringi       1.1.2   2016-10-01 CRAN (R 3.3.2)
    ##  stringr       1.1.0   2016-08-19 CRAN (R 3.3.2)
    ##  withr         2.1.1   2017-12-19 CRAN (R 3.3.3)
    ##  yaml          2.1.14  2016-11-12 CRAN (R 3.3.2)
