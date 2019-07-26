# NYC-Sewage
Protists in New York City Sewage


### DESCRIPTION

This fileset contains QIIME and R commands and outputs used to carry out the 18S rRNA gene analysis and shotgun metagenomic analysis in the manuscript:

Maritz, J. M., Ten Eyck, T. A., Alter, S. E., and Carlton, J. M. 2019. [Patterns of diversity associated with raw sewage in New York City.][Paper] *ISMEJ.* In press.


### DATA:

You will need to download the raw Illumina sequence data from the SRA under BioProjects PRJEB28033, [PRJEB26690][26690] and PRJEB23950.

You will also need to download the curated database used in this analysis.
Information on this can be found in my Github repository [Curated-SILVA-Database][github_database] and the the complete database can be downloaded from [Figshare][Database]

Alternatively, I have provided some QIIME formatted [OTU files](/Data) from the original analysis for download.

Links to the raw data and OTU files will be updated when the paper is published.


### REQUIREMENTS:

Trimmomatic 0.32, Qiime 1.9.0, ea_utils 1.1.2, python 2, USEARCH 8.0.1, blast 2.2.22

R packages: phyloseq 1.20.0, vegan 2.4-3, ggplot2 2.2.1, extrafont 0.17, gridExtra 2.2.1, SpiecEasi, igraph

[Paper]: https://www.nature.com/articles/s41396-019-0467-z
[26690]: https://www.ebi.ac.uk/ena/data/view/PRJEB26690
[github_database]: https://github.com/jmmaritz/Curated-SILVA-Database
[Database]: https://doi.org/10.6084/m9.figshare.3114850.v1
