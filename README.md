# FDFM

This repository provides the code and data considered in the work

Ofner, M., & Hörmann, S. (2023), "Reconstruction of functional data via approximate factor models of increasing rank".

## Installation

The R-package `FDFM` can be installed and loaded via the commands

```
devtools::install_github("maxofn/FDFM")
library(FDFM)
```

## Help

The main function for the reconstruction of functional data is `ReconstFD`. Type

```
help(ReconstFD)
```

for further details. Data of the real data application are contained in `temp_graz`.

## License

The package `FDFM` is licensed under GNU General Public License v3.0.

## References

Bai, J., & Ng, S. (2002). Determining the number of factors in approximate factor models. Econometrica, 70(1), 191-221.

Kneip, A., & Liebl, D. (2020). On the optimal reconstruction of partially observed functional data. The Annals of Statistics, 48(3), 1692–1717.

Kraus, D. (2015). Components and completion of partially observed functional data. Journal of the Royal Statistical Society: Series B: Statistical Methodology, 777-801.

Land Steiermark (2023). Air quality data. https://app.luis.steiermark.at/luft2/suche.php, Licensed under CC BY 4.0; accessed on March 28, 2023.

Onatski, A. (2010). Determining the number of factors from empirical distribution of eigenvalues. The Review of Economics and Statistics, 92(4), 1004-1016.

Yao, F., Müller, H. G., & Wang, J. L. (2005). Functional data analysis for sparse longitudinal data. Journal of the American statistical association, 100(470), 577-590.
