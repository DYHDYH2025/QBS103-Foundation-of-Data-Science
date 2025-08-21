# R-Foundation-of-Data-Science

- Final Submission
  
  Final submission contains all materials for the final project submission, including analysis files, output documents, code scripts, and visualization assets. The project focuses on statistical analysis of gene-related data, with a focus on covariates, gene expression patterns, and data visualization.

```filetree
QBS103-FOUNDATION-OF-DATA-SCIENCE/
├── README.md
├── sub1.Rmd
├── sub2.Rmd
└── Final_Submission/
    ├── FINAL_3_R_output.html
    ├── FINAL_3_R_output.pdf
    ├── Final_Project_latex_output.pdf
    ├── latex_proj/
    │   ├── boxplot.png
    │   ├── heatmap.png
    │   ├── histogram.png
    │   ├── main.tex
    │   ├── newplot.png
    │   ├── references.bib
    │   └── scatter.png
    └── R_proj/
        ├── QBS103_GSE157103_genes.csv
        ├── QBS103_GSE157103_series_matrix.csv
        └── FINAL_3.Rmd
```

- Submission 1

  Identify one gene, one continuous covariate, and two categorical covariates in the provided dataset. Note: Gene expression data and metadata are in two separate files and will need to be linked.
Generate the following three plots using ggplot2 for your covariates of choice:
Histogram for gene expression (5 pts)    
Scatterplot for gene expression and continuous covariate (5 pts)
Boxplot of gene expression separated by both categorical covariates (5 pts)
  
- Submission 2

  Build a function to create the plots you made for Presentation 1, incorporating any feedback you received on your submission. Your functions should take the following input: (1) the name of the data frame, (2) a list of 1 or more gene names, (3) 1 continuous covariate, and (4) two categorical covariates (10 pts)
Select 2 additional genes (for a total of 3 genes) to look at and implement a loop to generate your figures using the function you created (10 pts)
Present one of your boxplots in class. Be prepared to explain the gene and covariates you chose and comment on the distribution as if you were presenting your research findings. No slides are required, just bring your plot. In class, be prepared to provide constructive feedback for your classmates (5 pts)
