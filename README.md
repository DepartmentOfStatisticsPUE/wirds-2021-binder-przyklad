# Repozytorium na potrzeby przedmiotu WIRDS 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DepartmentOfStatisticsPUE/wirds-2021-binder-przyklad/main?urlpath=rstudio)

Aby binder działał potrzebuje następującego pliku:

+ `runtime.txt` -- określamy z jakiej wersji R będziemy korzystać oraz z jakiego dnia mają być pakiety (np. `r-2021-01-01`, `r-3.6-2021-01-01`).

Możemy założyć jakie pakiety mają być na w ramach tego obrazu. W takim razie powinniśmy utworzyć plik o nazwie `install.R`, który będzie zawierał skrypt R do instalcji pakietów. Na przykład:

```r
install.packages("tidyverse")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
```
