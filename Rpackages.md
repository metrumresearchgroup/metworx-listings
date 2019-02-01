Metworx v 3.1.0 R packages
================

R package compatibility wtih Metworx 3.1.0
=============================================

Please refer to this listing when having R package installation problems.

The following list of packages were installed to a temporary location on the Metworx 3.1.0 AMI as part of the validation process. These packages (at the indicated version) are *not still located on the AMI*, but are/were installable via CRAN. Newer versions of these packages may install without issue, but the versions listed should *always* be able to be installed on the indicated version of the AMI.

If you have additional R packages you'd like to have validated for installation upon the next AMI release, please open an issue in the [GitHub issue tracker](https://github.com/metrumresearchgroup/metworx-listings/issues) and let us know which ones you'd like added.

Listing of versions
===================

``` r
kable(installed.packages(validation_lib)[,c("Package","Version","Built","LibPath")], row.names = FALSE)
```

|Package        |Version     |Built |LibPath              |
|:--------------|:-----------|:-----|:--------------------|
|abind          |1.4-5       |3.5.1 |/data/validation-lib |
|acepack        |1.4.1       |3.5.1 |/data/validation-lib |
|akima          |0.6-2       |3.5.1 |/data/validation-lib |
|arm            |1.10-1      |3.5.1 |/data/validation-lib |
|ash            |1.0-15      |3.5.1 |/data/validation-lib |
|askpass        |1.1         |3.5.1 |/data/validation-lib |
|assertthat     |0.2.0       |3.5.1 |/data/validation-lib |
|backports      |1.1.3       |3.5.1 |/data/validation-lib |
|base64enc      |0.1-3       |3.5.1 |/data/validation-lib |
|BB             |2014.10-1   |3.5.1 |/data/validation-lib |
|bdsmatrix      |1.3-3       |3.5.1 |/data/validation-lib |
|BH             |1.69.0-1    |3.5.1 |/data/validation-lib |
|bibtex         |0.4.2       |3.5.1 |/data/validation-lib |
|bindr          |0.1.1       |3.5.1 |/data/validation-lib |
|bindrcpp       |0.2.2       |3.5.1 |/data/validation-lib |
|bit            |1.1-14      |3.5.1 |/data/validation-lib |
|bit64          |0.9-7       |3.5.1 |/data/validation-lib |
|bitops         |1.0-6       |3.5.1 |/data/validation-lib |
|blob           |1.1.1       |3.5.1 |/data/validation-lib |
|brew           |1.0-6       |3.5.1 |/data/validation-lib |
|broom          |0.5.1       |3.5.1 |/data/validation-lib |
|bvpSolve       |1.3.3       |3.5.1 |/data/validation-lib |
|callr          |3.1.1       |3.5.1 |/data/validation-lib |
|car            |3.0-2       |3.5.1 |/data/validation-lib |
|carData        |3.0-2       |3.5.1 |/data/validation-lib |
|caret          |6.0-81      |3.5.1 |/data/validation-lib |
|caTools        |1.17.1.1    |3.5.1 |/data/validation-lib |
|cellranger     |1.1.0       |3.5.1 |/data/validation-lib |
|checkmate      |1.9.1       |3.5.1 |/data/validation-lib |
|cli            |1.0.1       |3.5.1 |/data/validation-lib |
|clipr          |0.5.0       |3.5.1 |/data/validation-lib |
|coda           |0.19-2      |3.5.1 |/data/validation-lib |
|colorspace     |1.4-0       |3.5.1 |/data/validation-lib |
|covr           |3.2.1       |3.5.1 |/data/validation-lib |
|crayon         |1.3.4       |3.5.1 |/data/validation-lib |
|crosstalk      |1.0.0       |3.5.1 |/data/validation-lib |
|curl           |3.3         |3.5.1 |/data/validation-lib |
|data.table     |1.12.0      |3.5.1 |/data/validation-lib |
|DBI            |1.0.0       |3.5.1 |/data/validation-lib |
|dbplyr         |1.3.0       |3.5.1 |/data/validation-lib |
|deSolve        |1.21        |3.5.1 |/data/validation-lib |
|dfoptim        |2018.2-1    |3.5.1 |/data/validation-lib |
|digest         |0.6.18      |3.5.1 |/data/validation-lib |
|doParallel     |1.0.14      |3.5.1 |/data/validation-lib |
|DoseFinding    |0.9-16      |3.5.1 |/data/validation-lib |
|dparser        |0.1.8       |3.5.1 |/data/validation-lib |
|dplyr          |0.7.8       |3.5.1 |/data/validation-lib |
|evaluate       |0.12        |3.5.1 |/data/validation-lib |
|expm           |0.999-3     |3.5.1 |/data/validation-lib |
|extrafont      |0.17        |3.5.1 |/data/validation-lib |
|extrafontdb    |1.0         |3.5.1 |/data/validation-lib |
|fansi          |0.4.0       |3.5.1 |/data/validation-lib |
|fastmatch      |1.1-0       |3.5.1 |/data/validation-lib |
|fda            |2.4.8       |3.5.1 |/data/validation-lib |
|flexsurv       |1.1         |3.5.1 |/data/validation-lib |
|forcats        |0.3.0       |3.5.1 |/data/validation-lib |
|foreach        |1.4.4       |3.5.1 |/data/validation-lib |
|Formula        |1.2-3       |3.5.1 |/data/validation-lib |
|fs             |1.2.6       |3.5.1 |/data/validation-lib |
|gam            |1.16        |3.5.1 |/data/validation-lib |
|gamlss         |5.1-2       |3.5.1 |/data/validation-lib |
|gamlss.data    |5.1-0       |3.5.1 |/data/validation-lib |
|gamlss.dist    |5.1-1       |3.5.1 |/data/validation-lib |
|gamm4          |0.2-5       |3.5.1 |/data/validation-lib |
|gapminder      |0.3.0       |3.5.1 |/data/validation-lib |
|gdata          |2.18.0      |3.5.1 |/data/validation-lib |
|generics       |0.0.2       |3.5.1 |/data/validation-lib |
|geosphere      |1.5-7       |3.5.1 |/data/validation-lib |
|ggalt          |0.4.0       |3.5.1 |/data/validation-lib |
|ggmap          |2.6.2       |3.5.1 |/data/validation-lib |
|ggplot2        |3.1.0       |3.5.1 |/data/validation-lib |
|ggthemes       |4.0.1       |3.5.1 |/data/validation-lib |
|glue           |1.3.0       |3.5.1 |/data/validation-lib |
|gmp            |0.5-13.2    |3.5.1 |/data/validation-lib |
|gower          |0.1.2       |3.5.1 |/data/validation-lib |
|gplots         |3.0.1.1     |3.5.1 |/data/validation-lib |
|gridBase       |0.4-7       |3.5.1 |/data/validation-lib |
|gridExtra      |2.3         |3.5.1 |/data/validation-lib |
|gsubfn         |0.7         |3.5.1 |/data/validation-lib |
|gtable         |0.2.0       |3.5.1 |/data/validation-lib |
|gtools         |3.8.1       |3.5.1 |/data/validation-lib |
|haven          |2.0.0       |3.5.1 |/data/validation-lib |
|hexbin         |1.27.2      |3.5.1 |/data/validation-lib |
|highr          |0.7         |3.5.1 |/data/validation-lib |
|Hmisc          |4.2-0       |3.5.1 |/data/validation-lib |
|hms            |0.4.2       |3.5.1 |/data/validation-lib |
|HSAUR2         |1.1-17      |3.5.1 |/data/validation-lib |
|htmlTable      |1.13.1      |3.5.1 |/data/validation-lib |
|htmltools      |0.3.6       |3.5.1 |/data/validation-lib |
|htmlwidgets    |1.3         |3.5.1 |/data/validation-lib |
|httpuv         |1.4.5.1     |3.5.1 |/data/validation-lib |
|httr           |1.4.0       |3.5.1 |/data/validation-lib |
|igraph         |1.2.2       |3.5.1 |/data/validation-lib |
|inline         |0.3.15      |3.5.1 |/data/validation-lib |
|ipred          |0.9-8       |3.5.1 |/data/validation-lib |
|iterators      |1.0.10      |3.5.1 |/data/validation-lib |
|jpeg           |0.1-8       |3.5.1 |/data/validation-lib |
|jsonlite       |1.6         |3.5.1 |/data/validation-lib |
|knitr          |1.21        |3.5.1 |/data/validation-lib |
|labeling       |0.3         |3.5.1 |/data/validation-lib |
|Lahman         |6.0-0       |3.5.1 |/data/validation-lib |
|later          |0.7.5       |3.5.1 |/data/validation-lib |
|latticeExtra   |0.6-28      |3.5.1 |/data/validation-lib |
|lava           |1.6.4       |3.5.1 |/data/validation-lib |
|lazyeval       |0.2.1       |3.5.1 |/data/validation-lib |
|lme4           |1.1-19      |3.5.1 |/data/validation-lib |
|lmtest         |0.9-36      |3.5.1 |/data/validation-lib |
|lubridate      |1.7.4       |3.5.1 |/data/validation-lib |
|magrittr       |1.5         |3.5.1 |/data/validation-lib |
|manipulate     |1.0.1       |3.5.1 |/data/validation-lib |
|mapproj        |1.2.6       |3.5.1 |/data/validation-lib |
|maps           |3.3.0       |3.5.1 |/data/validation-lib |
|maptools       |0.9-4       |3.5.1 |/data/validation-lib |
|markdown       |0.9         |3.5.1 |/data/validation-lib |
|MatrixModels   |0.4-1       |3.5.1 |/data/validation-lib |
|maxLik         |1.3-4       |3.5.1 |/data/validation-lib |
|memoise        |1.1.0       |3.5.1 |/data/validation-lib |
|MEMSS          |0.9-2       |3.5.1 |/data/validation-lib |
|microbenchmark |1.4-6       |3.5.1 |/data/validation-lib |
|mime           |0.6         |3.5.1 |/data/validation-lib |
|minqa          |1.2.4       |3.5.1 |/data/validation-lib |
|miscTools      |0.6-22      |3.5.1 |/data/validation-lib |
|mlmRev         |1.0-6       |3.5.1 |/data/validation-lib |
|ModelMetrics   |1.2.2       |3.5.1 |/data/validation-lib |
|modelr         |0.1.2       |3.5.1 |/data/validation-lib |
|msm            |1.6.6       |3.5.1 |/data/validation-lib |
|mstate         |0.2.11      |3.5.1 |/data/validation-lib |
|muhaz          |1.2.6.1     |3.5.1 |/data/validation-lib |
|munsell        |0.5.0       |3.5.1 |/data/validation-lib |
|mvnfast        |0.2.5       |3.5.1 |/data/validation-lib |
|mvtnorm        |1.0-8       |3.5.1 |/data/validation-lib |
|n1qn1          |6.0.1-3     |3.5.1 |/data/validation-lib |
|nloptr         |1.2.1       |3.5.1 |/data/validation-lib |
|NMF            |0.21.0      |3.5.1 |/data/validation-lib |
|numDeriv       |2016.8-1    |3.5.1 |/data/validation-lib |
|nycflights13   |1.0.0       |3.5.1 |/data/validation-lib |
|openssl        |1.2.1       |3.5.1 |/data/validation-lib |
|openxlsx       |4.1.0       |3.5.1 |/data/validation-lib |
|optextras      |2016-8.8    |3.5.1 |/data/validation-lib |
|optimx         |2018-7.10   |3.5.1 |/data/validation-lib |
|pander         |0.6.3       |3.5.1 |/data/validation-lib |
|pbkrtest       |0.4-7       |3.5.1 |/data/validation-lib |
|PBSddesolve    |1.12.2      |3.5.1 |/data/validation-lib |
|PBSmodelling   |2.68.6      |3.5.1 |/data/validation-lib |
|pillar         |1.3.1       |3.5.1 |/data/validation-lib |
|pkgconfig      |2.0.2       |3.5.1 |/data/validation-lib |
|pkgmaker       |0.27        |3.5.1 |/data/validation-lib |
|PKPDmodels     |0.3.2       |3.5.1 |/data/validation-lib |
|plm            |1.7-0       |3.5.1 |/data/validation-lib |
|plogr          |0.2.0       |3.5.1 |/data/validation-lib |
|plotly         |4.8.0       |3.5.1 |/data/validation-lib |
|plotrix        |3.7-4       |3.5.1 |/data/validation-lib |
|plyr           |1.8.4       |3.5.1 |/data/validation-lib |
|png            |0.1-7       |3.5.1 |/data/validation-lib |
|PreciseSums    |0.3         |3.5.1 |/data/validation-lib |
|prettyunits    |1.0.2       |3.5.1 |/data/validation-lib |
|processx       |3.2.1       |3.5.1 |/data/validation-lib |
|prodlim        |2018.04.18  |3.5.1 |/data/validation-lib |
|progress       |1.2.0       |3.5.1 |/data/validation-lib |
|proj4          |1.0-8       |3.5.1 |/data/validation-lib |
|promises       |1.0.1       |3.5.1 |/data/validation-lib |
|proto          |1.0.0       |3.5.1 |/data/validation-lib |
|ps             |1.3.0       |3.5.1 |/data/validation-lib |
|purrr          |0.3.0       |3.5.1 |/data/validation-lib |
|quadprog       |1.5-5       |3.5.1 |/data/validation-lib |
|quantreg       |5.38        |3.5.1 |/data/validation-lib |
|R6             |2.3.0       |3.5.1 |/data/validation-lib |
|Rcgmin         |2013-2.21   |3.5.1 |/data/validation-lib |
|RColorBrewer   |1.1-2       |3.5.1 |/data/validation-lib |
|Rcpp           |1.0.0       |3.5.1 |/data/validation-lib |
|RcppArmadillo  |0.9.200.7.0 |3.5.1 |/data/validation-lib |
|RcppEigen      |0.3.3.5.0   |3.5.1 |/data/validation-lib |
|RcppRoll       |0.3.0       |3.5.1 |/data/validation-lib |
|readr          |1.3.1       |3.5.1 |/data/validation-lib |
|readxl         |1.2.0       |3.5.1 |/data/validation-lib |
|recipes        |0.1.4       |3.5.1 |/data/validation-lib |
|registry       |0.5         |3.5.1 |/data/validation-lib |
|rematch        |1.0.1       |3.5.1 |/data/validation-lib |
|reprex         |0.2.1       |3.5.1 |/data/validation-lib |
|reshape2       |1.4.3       |3.5.1 |/data/validation-lib |
|rex            |1.1.2       |3.5.1 |/data/validation-lib |
|RgoogleMaps    |1.4.3       |3.5.1 |/data/validation-lib |
|rio            |0.5.16      |3.5.1 |/data/validation-lib |
|rJava          |0.9-10      |3.5.1 |/data/validation-lib |
|rjson          |0.2.20      |3.5.1 |/data/validation-lib |
|RJSONIO        |1.3-1.1     |3.5.1 |/data/validation-lib |
|rlang          |0.3.1       |3.5.1 |/data/validation-lib |
|rmarkdown      |1.11        |3.5.1 |/data/validation-lib |
|R.methodsS3    |1.7.1       |3.5.1 |/data/validation-lib |
|rngtools       |1.3.1       |3.5.1 |/data/validation-lib |
|ROCR           |1.0-7       |3.5.1 |/data/validation-lib |
|R.oo           |1.22.0      |3.5.1 |/data/validation-lib |
|rootSolve      |1.7         |3.5.1 |/data/validation-lib |
|RSQLite        |2.1.1       |3.5.1 |/data/validation-lib |
|rtf            |0.4-13      |3.5.1 |/data/validation-lib |
|Rttf2pt1       |1.3.7       |3.5.1 |/data/validation-lib |
|R.utils        |2.7.0       |3.5.1 |/data/validation-lib |
|rvest          |0.3.2       |3.5.1 |/data/validation-lib |
|Rvmmin         |2018-4.17   |3.5.1 |/data/validation-lib |
|RxODE          |0.8.0-9     |3.5.1 |/data/validation-lib |
|sandwich       |2.5-0       |3.5.1 |/data/validation-lib |
|scales         |1.0.0       |3.5.1 |/data/validation-lib |
|sde            |2.0.15      |3.5.1 |/data/validation-lib |
|selectr        |0.4-1       |3.5.1 |/data/validation-lib |
|sessioninfo    |1.1.1       |3.5.1 |/data/validation-lib |
|setRNG         |2013.9-1    |3.5.1 |/data/validation-lib |
|sfsmisc        |1.1-3       |3.5.1 |/data/validation-lib |
|shiny          |1.2.0       |3.5.1 |/data/validation-lib |
|sourcetools    |0.1.7       |3.5.1 |/data/validation-lib |
|sp             |1.3-1       |3.5.1 |/data/validation-lib |
|SparseM        |1.77        |3.5.1 |/data/validation-lib |
|SQUAREM        |2017.10-1   |3.5.1 |/data/validation-lib |
|stargazer      |5.2.2       |3.5.1 |/data/validation-lib |
|stringi        |1.2.4       |3.5.1 |/data/validation-lib |
|stringr        |1.3.1       |3.5.1 |/data/validation-lib |
|svUnit         |0.7-12      |3.5.1 |/data/validation-lib |
|sys            |2.1         |3.5.1 |/data/validation-lib |
|tibble         |2.0.1       |3.5.1 |/data/validation-lib |
|tidyr          |0.8.2       |3.5.1 |/data/validation-lib |
|tidyselect     |0.2.5       |3.5.1 |/data/validation-lib |
|tidyverse      |1.2.1       |3.5.1 |/data/validation-lib |
|timeDate       |3043.102    |3.5.1 |/data/validation-lib |
|tinytex        |0.10        |3.5.1 |/data/validation-lib |
|tnet           |3.0.14      |3.5.1 |/data/validation-lib |
|ucminf         |1.1-4       |3.5.1 |/data/validation-lib |
|utf8           |1.1.4       |3.5.1 |/data/validation-lib |
|viridis        |0.5.1       |3.5.1 |/data/validation-lib |
|viridisLite    |0.3.0       |3.5.1 |/data/validation-lib |
|whisker        |0.3-2       |3.5.1 |/data/validation-lib |
|withr          |2.1.2       |3.5.1 |/data/validation-lib |
|xfun           |0.4         |3.5.1 |/data/validation-lib |
|XML            |3.98-1.16   |3.5.1 |/data/validation-lib |
|xml2           |1.2.0       |3.5.1 |/data/validation-lib |
|xpose4         |4.6.1       |3.5.1 |/data/validation-lib |
|xtable         |1.8-3       |3.5.1 |/data/validation-lib |
|yaml           |2.2.0       |3.5.1 |/data/validation-lib |
|zip            |1.0.0       |3.5.1 |/data/validation-lib |
|zoo            |1.8-4       |3.5.1 |/data/validation-lib |

Session info
============
```{r}
─ Session info ─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
 setting  value                       
 version  R version 3.5.1 (2018-07-02)
 os       Ubuntu 14.04.5 LTS          
 system   x86_64, linux-gnu           
 ui       RStudio                     
 language (EN)                        
 collate  en_US.UTF-8                 
 ctype    en_US.UTF-8                 
 tz       Etc/UTC                     
 date     2019-02-01                  

─ Packages ─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
 ! package     * version date       lib source        
 R assertthat    0.2.0   <NA>       [?] <NA>          
 R cli           1.0.1   <NA>       [?] <NA>          
 R crayon        1.3.4   <NA>       [?] <NA>          
   highr         0.7     2018-06-09 [1] CRAN (R 3.5.1)
   knitr       * 1.21    2018-12-10 [1] CRAN (R 3.5.1)
   rstudioapi    0.8     2018-10-02 [4] CRAN (R 3.5.1)
 R sessioninfo * 1.1.1   <NA>       [?] <NA>          
 R withr         2.1.2   <NA>       [?] <NA>          
   xfun          0.4     2018-10-23 [1] CRAN (R 3.5.1)
```
