---
title: "Visualización Interactiva de Datos con Shiny"
output:
  html_document:
    df_print: paged
weight: 1
---



__Dates__: 17 al 18 de agosto, 2019<br>
__Location__: Valparaiso, Chile<br>
__Venue__: [IFOP](https://www.ifop.cl), Almte. Manuel Blanco Encalada 839, Valparaiso

El Instituto de Fomento Pesquero, en su interés por el perfeccionamiento continuo, provee cursos y 
alternativas de entrenamiento dentro de los cuales se enmarca este curso. El objetivo principal es 
dar una introducción introducir al uso de Shiny para visualizar datos en forma interactiva y 
publicar estas aplicaciones en una pagina web para ser utilizado por usuarios que no tienen conociminetos de `R`.

Al final de este curso se espera que los participantes tengan familiaridad con `Shiny` y ser capaces de
construir una aplicación simple que permita la manipulacion de unos pocos parámetros para controlar la 
informacion que se despliega en un gráfico interactivo.

Este taller de 2 días es un traller para introducir en forma rápida y simple `Shiny` y dar las herramientas 
básicas necesarias para permitir el auto-aprendizaje. 

<p align="center">
  <img src="https://community.rstudio.com/uploads/default/original/1X/c017cef9c13bc937df73659d3b5b1411a39c7ed2.png" width="15%" height="15%" />
</p>

## Sinopsis:

Temas a incluir en el taller:

* Introducción al uso de RStudio y Shiny
* ¿Que esperamos comunicar?
* Preparacion de los datos
* ggplot para visualzación de datos
* Gráficos interactivos con shiny

Para mas detalles de como prepararse para el taller, ver sección [Preparándose para el Taller] (más abajo).

## Materiales

- [Introducción a Shiny](/materials/Shiny/index.html)


## Organizadores

|Nombre         | Email              |
|-------------|--------------------|
|Jorge Cornejo| jorge.cornejo@ifop.cl |
|Alguien Máx? | alguien.mas@ifop.cl |

## Agradecimientos

El trabajo para preparar estos documentos esta basado en:


## Preparándose para el Taller

### Software Requerido

Necesitaremos usar un _navegador web_, `R`, RStudio, y `git`. Por favor asegúrese de que todos estos estén instalados en su computador portátil, las versiones mínimas requeridas son:

- **R:** Usaremos R versión 3.6.0, la que puede ser instalada desde [CRAN](https://cran.rstudio.com)

- **RStudio**: Para bajar RStudio, visite [RStudio's download page](https://www.rstudio.com/products/rstudio/download/).
  *Si no está seguro que es una versión reciente, por favor bájela y realice una actualización*
    
- **Paquete de R:** Por favor asegúrese de tener instalado y actualizados los siguientes paquetes de R:

    - Shiny
    - dplyr
    - DT
    - ggplot2

    
    Puede instalar rápidamente todos estos paquetes corriento el siguiente código en su `R`:

    ```r
    packages <- c("shiny", "dplyr", "ggplot2", "DT", "tidyr")
    ```
    
    ```r
    for (package in packages) {
      if (!(package %in% installed.packages())) {
        install.packages(package)
      }
    }
    ```

- **git:** [Descargar git](https://git-scm.com/downloads) e instalarlo en su sistema.
- **GitHub:** Usaremos [GitHub](https://github.com), por favor crear (o recordar) su _login_ a GitHub.

### Refrescando sus destrezas

Este taller asume un nivel básico de experiencia usando R para propósitos científicos y estadísticos.
Sin embargo, sabes que no todos están en el mismo lugar en términos de familiaridad con la herramientas que usaremos.
Si Ud. quiere refrescar su experiencia en R antes del taller, le recomiendo usar los siguientes recursos: 

__Están en inglés, pero prometo buscar alternativas en español y las agregaré en la medida que las vaya encontrando__

- The [Data Scientist with R](https://www.datacamp.com/tracks/data-scientist-with-r) track at [DataCamp](https://www.datacamp.com)
- The [Introduction to R](http://www.datacarpentry.org/R-ecology-lesson/01-intro-to-r.html) lesson in [Data Carpentry's R for data analysis](http://www.datacarpentry.org/R-ecology-lesson/) course.
- The QCBS [Introduction to R](https://qcbs.ca/wiki/r) lesson
- [RStudio's R Programming](https://www.rstudio.com/online-learning/) page

Si eres fan de las _hojas de referencia_ (cheat sheets), [RStudio](https://www.rstudio.com) tiene un listado de algunas en su pagina [Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/).

En particular, revise:

* Base R
* Data Import 
* Data Transformation with dplyr 
* Shiny
* Data Visualization with ggplot2

## Participantes

|Nombre         | Email              | Afiliación           |
|-------------|--------------------|----------------------|


## Consultas y comentarios

Estoy complemente abierto a responder consultas, comentarios y sugerencias. Por favor déjelos en como [Nuevo tema](https://github.com/cornejotux/claseRMarkdown/issues) (_New Issue_) en la pagina del repositorio en `GitHub`, de esa forma queda asociado al material y no se me pierde en los miles de e-mail que me llegan a diario.
