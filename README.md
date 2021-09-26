
<!-- README.md is generated from README.Rmd. Please edit that file -->

# comidistar <img src='man/figures/logo.png' align="right" height="139" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/gongcastro/comidistar/workflows/R-CMD-check/badge.svg)](https://github.com/gongcastro/comidistar/actions)
<!-- badges: end -->

**comidistar** es un paquete de R que contiene una base de datos con las
puntuaciones de las catas a ciegas de [El
Comidista](https://elcomidista.elpais.com/). También contiene algunas
funciones para trabajar con los datos y visualizarlos más fácilmente.
Las puntuaciones y datos adicionales sobre los productos de las catas
fueron transcritos manualmente a partir de los vídeos subidos al canal
de [YouTube](https://www.youtube.com/channel/UCoIJrrwXy_mlr1WkC4vaTnA)
de El Comidista. La documentación del paquete está disponible en este
[link](https://gongcastro.github.io/comidistar/), junto con algunas
viñetas y tutoriales.

## Instalación

Puedes instalar comidistar ejecutando el siguiente código:

``` r
# podrías necesitar instalar el paquete devtools primero
# install.packages("devtools")
devtools::install_github("gongcastro/comidistar")
```

## Ejemplo

Puedes cargar la base de datos como un *data frame* así:

``` r
library(comidistar)
data("puntuaciones")
```
