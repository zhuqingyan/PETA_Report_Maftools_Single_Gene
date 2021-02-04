# PETA_Report_Maftools_Single_Gene
PETA report template using IR kernel to draw frequently used figures of single gene.

# Author
Qinyang Zhu</br>
zhuqingyan@genomics.cn

# Input data format
All genomics records with mutation as TCGA's MAF format.

# Analysis
Use [maftools](http://bioconductor.org/packages/release/bioc/vignettes/maftools/inst/doc/maftools.html) library:</br>
1.Shows clinical data associated with samples.</br>
2.Shows sample summry.</br>
3.Shows gene summary.</br>
4.Maf summary.</br>
5.Ti\/Tv.</br>
6.Lollipop plots for amino acid changes.</br>
7.Survival analysis.</br>

# Usage
Supposed that you have access to BGI-PETA database and to the selected data set:</br>

```
$jwr -i PETA_Report_Maftools_Single_Gene.ipynb -o PETA_Report_Maftools_Single_Gene.html --json_str xxx --token xxx
```

'xxx' should replace your information.
