Dpulex_BSGenome
===============

A Bioconductor/Biostrings Genome (BSGenome) package for the new PA42 assembly of Daphnia pulex

After cloning this repository, you can create (or 'forge') a BSgenome object using the following commands (see also http://www.bioconductor.org/packages/release/bioc/vignettes/BSgenome/inst/doc/BSgenomeForge.pdf):

Using R: 

> library(BSgenome)
> forgeBSgenomeDataPkg("path/to/DpPA42_seed")

Once this is complete, exit R and enter the following commands on your Unix/Linux command line: 
(this presumes this is in your working directory, otherwise enter the path to this folder and then the folder name)

> R CMD INSTALL BSgenome.Dpulex.PA42 
(finally, this will install the package in your R library)

If you have any questions or encounter a problem with this package, please create an issue on his account or email me directory at rtraborn 'at' indiana 'dot' edu. This package will be updated as new versions of the assembly become available

