# Cell atlas plots

Version 1.0 (18-Apr-2022)
It is noted in the next version update, I will need to undertake the following:
- state the colour scheme annotation
- update the description 
- detail the code replacement to customise plots for TPM instead of NX values

This is the R notebook (file name: Cell_atlas_plots.Rmd) for generating a PDF cell atlas plots for any given gene(s) of interest, highlighting cell lines that are normal (green) or cancer derived (blue). In the plots you get directly from cell atlas, this is not highlighted and so this information is not obvious upon data visualisation.  

Cell atlas is from the human protein atlas containing RNA-seq data from 69 cell lines. The [data](https://www.proteinatlas.org/about/download) is publicly available under the section 'RNA HPA cell line gene data'. More information about this database is found [here](https://www.proteinatlas.org/humanproteome/cell+line) and the list of cell lines is found [here](https://www.proteinatlas.org/learn/cellines).

Note that as per the plots you can get directly from cell atlas, the NX (normalised) values will be used for RNA expression. However, TPM could be plotted potentially. In this instance, NX needs to be replaced with TPM upon column selection. This code replacement for plotting TPM would be indicated in the code below if this customisation needs to be applied. 

README file to be further updated to include information of the individual files in code section. 
