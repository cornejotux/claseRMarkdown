---
title: "Investigación reproducible: Una Introduccion con RMarkdown"
output:
  html_document:
    df_print: paged
weight: 1
---



__Dates__: 17 al 18 de julio, 2019<br>
__Location__: Valparaiso, Chile<br>
__Venue__: [IFOP](https://www.ifop.cl), Almte. Manuel Blanco Encalada 839, Valparaiso

El Instituto de Formento Pesquero, en su interes por el perfeccionamiento continuo provee cursos y 
alternativas de entrenamiento, dentro del cual se enmarca este curso, cuyo objetivo principal es introducir
en el tema de la _Investigación reproducible_, incentivar su uso dentro de IFOP y desarrollar las destresas 
necesarias en el uso de [R](https://www.r-project.org/), [RStudio](https://www.rstudio.com/) y
[RMarkdown](https://rmarkdown.rstudio.com/) como herramientas para la _ciencia de datos_ e _investifacion reproducible_ gratuitas y ampliamente utilizadas en la comunidad científica. 

Al final de este curso se espera que los participantes tengan familiaridad con RMarkdown para utilizarlo para generar
reportes en formato PDF y HTML que puedan compartir con otros investigadores, donde se describa los pasos para reproducir
a cabalidad los resultados, desde la lectura de datos, su manipulacion, análisis y produccion de gráficos y tablas, 

Este taller de 3 dias es una vision general sobre buenas prácticas, herramientas para la ciencia de datos y describe algunos pasos y métodos prácticos para documentar con facilidad el trabajo y asegurar si replicabilidad. 


## Sinopsis:

Temas a incluir en el taller:

* Intrucción al uso de RStudio y RMarkdown
* ¿Qué es Investigación reproducible?
* Analisis literal con RMarkdown
* Control de versiones con GitHub (y paginas web)
* Modelamiento, limpieza y manejo de datos


Para mas detalles de como prepararse para el tales, ver seccion "**Preparse para el taller**" (mas abajo).

## Materiales

- [Intro a RMarkdown](/materials/RMarkdown/index.html)


## Organizadores

|Name         | Email              |
|-------------|--------------------|
|Jorge Cornejo| jorge.cornejo@ifop.cl |
|Alguien Máx? | alguien.mas@ifop.cl |

## Agradecimientos

El trabajo para preparar estos documentos esta basado en:

- [NCEAS SASAP-Training](https://github.com/NCEAS/sasap-training) 
- [NCEAS Arctic Data Center](https://github.com/NCEAS/arctic-data-training) 

## Preparandose para el Taller

### Software Requido

Necesitaremos usar un _navegador web_, `R`, RStudio, y `git`. Por favor asegurese de que todos estos estén instaladados en su computador portatil, las versiones mínimas requeridas son:

- **R:** Usaremos R version 3.5.2, which you can download and install from [CRAN](https://cran.rstudio.com)

- **RStudio**: To download RStudio, visit [RStudio's download page](https://www.rstudio.com/products/rstudio/download/).
  *If you don't know how up to date your version of RStudio is, please download an updated copy and install it*
    
- **R packages:** Please be sure you have installed or updated the following packages:

    - devtools
    - dplyr
    - DT
    - ggplot2
    - leaflet
    - tidyr
    
    You can install these packages quickly by running the following two code snippets:

    ```r
    packages <- c("dataone", "datapack", "devtools", "dplyr", "EML", "ggplot2", "readxl", "tidyr")
    ```
    
    ```r
    for (package in packages) {
      if (!(package %in% installed.packages())) {
        install.packages(package)
      }
    }
    ```

- **git:** [Download git](https://git-scm.com/downloads) and install it on your system.
- **GitHub:** We will be using [GitHub](https://github.com) so you will need create (or remember your existing) GitHub login

### Refresh your skills

This workshop assumes a base level of experience using R for scientific and statistical analyses.
However, we realize that not everyone will be at the same place in terms of familiarity with the tools we'll be using.
If you'd like to brush up on your R skills prior to the workshop, check out this list of resources we like:

- The [Data Scientist with R](https://www.datacamp.com/tracks/data-scientist-with-r) track at [DataCamp](https://www.datacamp.com)
- The [Introduction to R](http://www.datacarpentry.org/R-ecology-lesson/01-intro-to-r.html) lesson in [Data Carpentry's R for data analysis](http://www.datacarpentry.org/R-ecology-lesson/) course.
- The QCBS [Introduction to R](https://qcbs.ca/wiki/r) lesson
- [RStudio's R Programming](https://www.rstudio.com/online-learning/) page

If you're a fan of cheat sheets, [RStudio](https://www.rstudio.com) provides some fantastic ones on their [Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/) page.
*Please make sure to print ahead of time if you prefer hard copies.*
In particular, check out:

* Base R
* Data Import 
* Data Transformation with dplyr 
* R Markdown
* Data Visualization with ggplot2
* R Markdown Reference Guide 
* The leaflet package

## Participants

|Name         | Email              |Affiliation           |
|-------------|--------------------|----------------------|
Adam Schneider|amschne@umich.edu|University of Michigan|
Aleksey Sheshukov|ashesh@ksu.edu|Kansas State University|
Alexis C Garretson|alexis@garretson.net|Brigham Young University|
Ali Paulson|alison.paulson@msstate.edu|Mississippi State|
Anastasija Mensikova|mensikova.anastasija@gmail.com|George Washington University|
Anna Nesterovich|annanest@iastate.edu|Iowa State|
Caixia Wang|cwang12@alaska.edu|University of Alaska - Anchorage|
Christina Minions|cminions@whrc.org|Woods Hole Research Center|
Desheng Liu|liu.738@osu.edu|Ohio State University|
Helene Angot|helene.angot@colorado.edu|University of Colorado - Boulder|
Ian Baxter|itbaxter@ucsb.edu|UC Santa Barbara|
Kelly Kapsar|kelly.kapsar@gmail.com|Michigan State|
Komi Messan|Komi.S.Messan@erdc.dren.mil|US Army Corps of Engineers|
Olaf Kuhlke|okuhlke@d.umn.edu|University of Minnesota - Duluth|
Rebecca Finger-Higgens|rebecca.finger@gmail.com|Dartmouth College|
Sanghoon Kang|sanghoon_kang@baylor.edu|Baylor University|
Sara Pedro|sara.pedro@uconn.edu|University of Connecticut|
Susan L. Howard|showard@esr.org|Earth and Space Research|
Yiyi Huang|yiyi063@email.arizona.edu|University of Arizona|
