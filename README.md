[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Don't judge me](https://img.shields.io/badge/Language-Perl_5-steelblue.svg)

# mini-outbreak

Small WGS dataset for testing bacterial outbreak analysis pipelines

## Motivation

There are already good curated 
[WGS data sets for bacterial outbreaks](https://github.com/WGS-standards-and-analysis/datasets).
These are real full-sized FASTQ files which are too large
for quick local testing or within continuous integration (CI) environments 
like TRAVIS-CI and CIRCLE.

This project aims to be small but complete:
* More than 10 isolates, which can be sub-setted
* Different reference genomes
* Small genome sizes < 100 kbp
* Each genome 
** MLST typeable
** 0+ AMR genes
** 0+ virulence genes

## Using the data

Coming soon.

## License

mini-outbreak is free software, released under the
[GPL 3.0](https://raw.githubusercontent.com/tseemann/mini-outbreak/master/LICENSE).

## Issues

Please submit suggestions and bug reports to the
[Issue Tracker](https://github.com/tseemann/mini-outbreak/issues)

## Author

[Torsten Seemann](https://twitter.com/torstenseemann)
