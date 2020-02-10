
This repository holds additional information and scripts for generating the figures in the commentary "Develop codes of practice for computational text analysis in energy social science" by Finn Müller-Hansen, Max W. Callaghan and Jan C. Minx.

## Data sources

The data for the number of publications in Figure 1 was downloaded from [Scopus](https://www.scopus.com) on January 31, 2020 using the following queries with *Advanced search*:

```
SUBJAREA ( ( arts  OR  busi  OR  deci  OR  econ  OR  psyc  OR  soci )  AND  ener )
SUBJAREA ( ( arts  OR  busi  OR  deci  OR  econ  OR  psyc  OR  soci )  AND NOT  ener )
SUBJAREA ( ener  AND NOT  ( arts  OR  busi  OR  deci  OR  econ  OR  psyc  OR  soci ) )
```
To download the data, we ran the queries separately and used the *Export* tool on the *Analyze search results* page. They are included in this repository (files "Scopus-...-Analyze-Year.csv").

## Recreating figures

To rerun the code, you need a python environment  (we recommend using [Anaconda](https://docs.anaconda.com/anaconda/install/)) with [jupyter](https://jupyter.org/install) and the packages named in the first cell of the notebook. [Start up a notebook](https://jupyter.readthedocs.io/en/latest/running.html) in your browser, go to the directory in which the jupyter notebook files (.ipynb) are located and open them. The figures can be recreated running all cells in the notebook.

From these raw versions, the final figures were assembled with [Inkscape](https://inkscape.org/) using the [Tex Text](https://textext.github.io/textext/) plugin.


