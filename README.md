# HiCExplorer_update_version
Added additional functions to basic HiCExplorer.
Replace needed files to original HiCExplorer installation folder, typical at python library HiCExplorer folder.


## hicPlotMatrix.py
1. change in chromosomeOrder parameter: if only one "@" is present in the chromosome order, like "chr1 chr2 chr3 @ chr4 chr5 chr6", the resulting plot would be "chr1 chr2 chr3" at X axis and "chr4 chr5 chr6" at Y axis, i.e. the plot only contains the interchromosome contact matrix between "chr1 chr2 chr3" and "chr4 chr5 chr6". Useful when  ploting Interactions between parternal and maternal genome.

