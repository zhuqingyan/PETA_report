# PETA-report
PETA-report template using IR kernel to draw frequently used figures


# Author
Qinyang Zhu</br>
zhuqingyan@genomics.cn

# Input data format
All genomics records with mutation as TCGA's MAF format.

# Analysis
Use [GenVisR](https://bioconductor.org/packages/release/bioc/vignettes/GenVisR/inst/doc/Intro.html) library:</br>
1.waterfall (mutation overview graphic)</br>


# Usage
Supposed that you have access to BGI-PETA database and to the selected data set:</br>

```
$jwr -i PETA_report_R_Genomic_Visualizations.ipynb -o PETA_report_R_Genomic_Visualizations.html --json_str xxx --token xxx

```
'xxx' should replace your information.
