
# aprendeR

<!-- badges: start -->
<!-- badges: end -->

El Objetivo del paquete aprendeR es facilitar que nuevas personas puedan 
    R moderno con una curva de aprendizaje baja, y evitando que el inglés sea
    una barrera para que se puedan centrar en el aprendizaje competencial de R.
    Se incluyen traducciones al castellano de tutoriales presentes 
    en otros paquetes (learnr, tutorial.helpers, r4ds.tutorials, ...),
    y eventualmente nuevos tutoriales más adelante.

## Instalación

Para instalarlo la primera vez desde [GitHub](https://github.com/) directamente y cargarlo en memoria para poder utilizarlo, puedes ejecutar en una consola de R:

``` r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("xavidp/aprendeR")
library("aprenderR")
```

## Uso de los tutoriales

Para seguir los tutoriales, tienes dos formas

  1. Puedes levantar una ventana emergente con el tutorial que desees ejecutando este tipo de instrucción para el tutorial de interés:
    ```
    learnr::run_tutorial("010-puesta-a-punto", package = "aprendeR")
    ```
    
  1. O puedes revisar la lista de tutoriales disponibles (de los paquetes cargados en memoria) a través del panel superior derecho de RStudio, en la pestaña que dice *"Tutorials"*.
  (si no ves la pestaña, intenta actualizar la versión de RStudio de que dispones)


Lista de tutoriales diponibles por ahora:

    (Spanish-tutorial-name <- package/English-tutorial-name) :

    - 010-puesta-a-punto              <- learnr/ex-setup-r 
    - 020-empezando                   <- tutorial.helpers/getting-started
    - 030-conceptos-basicos-de-datos  <- learnr/ex-data-basics
    - 040-rstudio-y-codigo            <- r4ds.tutorials/rstudio-and-code
    - 050-filtrar-datos               <- learnr/ex-data-filter
    - 060-mutar-datos                 <- learnr/ex-data-mutate
    - 070-resumir-datos               <- learnr/ex-data-sumarise
    - 100-hojas-de-calculo            <- r4ds.tutorials/spreadsheets
    
    
    Many thanks to the all the authors of the source English tutorials!


Por ahora (Primavera-Verano 2023) se estan traduciendo al castellano, como compromiso de equilibrio para disponer de mayor audiencia en esta fase inicial (y posible gente de todas partes que quiera apuntarse al carro a traducir más cosas del inglés para personas latinas para las que leyer del inglés sea un problema extra añadido mientras quieren aprender a hacer ciencia de datos con R). Y más adelante (o cuando ya esté más estable el proyecto de paquete para ayudar a aprender R), las personas catalanoparlantes podemos realizar la versión catalana también entre personas voluntarias que puedan ayudar, etc. (o en los idiomas que quieran otras personas)
