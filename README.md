# PETA_Report_Maftools_Single_Gene
PETA report template using IR kernel to draw frequently used figures of single gene.

# Author
Qinyang Zhu
zhuqingyan@genomics.cn

# Input data format
All genomics records with mutation as TCGA's MAF format.

# Analysis
Use maftools library:
1.waterfall (mutation overview graphic)

# Usage
Supposed that you have access to BGI-PETA database and to the selected data set:

```
$jwr -i PETA_Report_Maftools_Single_Gene.ipynb -o PETA_Report_Maftools_Single_Gene.html --json_str xxx --token xxx
```

'xxx' should replace your information.
