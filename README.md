# bcg_influenza
This is the R code for the transcriptomic analyses in the manuscript "Influenza coinfection inhibits control of mycobacterial infection in a human challenge model". 

Authors:
Claire M Broderick1, Oliver Powell1, Sam Nichols1, Giselle D’Souza1, Dominic Habgood-Coote1, Carlota Miranda-Sole1, Emily M Whettlock1, Zoe Gardener1, Emma Bergstrom1, Victoria Wright1, Christopher W Woods2, Christopher Chiu1, Sandra Newton1†, Elizabeth Whittaker1,3, Michael Levin1*, Myrsini Kaforou1*

Affiliations:
1 Department of Infectious Disease, Imperial College London, UK
2 Department of Medicine, Duke University Medical Center, Durham, NC, USA
3 Department of Paediatric Infectious Diseases, Imperial College Healthcare NHS Trust, London, UK.




The  software/ R packages used in the analyses are listed below, with the versions and installation instructions provided. All are typically installed within minutes on a "normal" desktop computer. No non-standard hardware required. 

R (version 4.0.4).
 
biomaRt (version 2.46.3, accessed database Sept 2022). https://bioconductor.org/packages/release/bioc/html/biomaRt.html. Dependencies: R, methods. No system requirements.

DESeq2 (version 1.30.1). https://bioconductor.org/packages/release/bioc/html/DESeq2.html. Dependencies: S4Vectors, IRanges, GenomicRanges, SummarizedExperiment. No system requirements.

maSigPro (version 1.78.0). https://www.bioconductor.org/packages/release/bioc/html/maSigPro.html. Dependencies: R. No system requirements.

rstatix (version 0.7.2). https://cran.r-project.org/web/packages/rstatix/index.html. Dependencies: R. No system requirements. (Kassambara, A. rstatix: Pipe-Friendly Framework for Basic Statistical Tests, 2023).
 
ggplot2 (version 3.5.1) https://cran.r-project.org/web/packages/ggplot2/index.html. Dependencies: R. No system requirements.

pheatmap (version 1.0.12) https://cran.r-project.org/web/packages/pheatmap/. Dependencies: R. No system requirements. (Kolde, R. pheatmap: Pretty Heatmaps, 2018).

ggbreak (version 0.1.4) https://cran.r-project.org/web/packages/ggbreak/index.html. Dependencies: R. No system requirements. (Xu, S., Chen, M., Feng, T., et al. Use ggbreak to Effectively Utilize Plotting Space to Deal With Large Datasets and Outliers. Front Genet 12, 774846, 2021).

ggsignif (version 0.6.4) (Ahlmann-Eltze, C. & Patil, P. ggsignif: R Package for Displaying Significance Brackets for 'ggplot2'. PsyArxiv, 2021).

gridExtra (version 2.3) (Auguie, B. & Antonov, A. gridExtra: Miscellaneous Functions for "Grid" Graphics, 2017).

cowplot (version 1.1.3) (Wilke, C.O. cowplot – Streamlined plot theme and plot annotations for ggplot2, 2016).

dplyr (version 1.1.4) Wickham H, F.R., Henry L, Müller K, Vaughan D. dplyr: A Grammar of Data Manipulation.  (2023).

tidyr (version 1.3.1) Wickham H, V.D., Girlich M tidyr: Tidy Messy Data.  (2023).

scales (version 1.4.0).	Wickham H, P.T., Seidel D. scales: Scale Functions for Visualization.  (2023).


The data is available to download from ArrayExpress, accession E-MTAB-15137.

Sequential instructions to run the code can be found in the Code file.

Expected run time to run all code: ~1 hour on a "normal" desktop computer.

Expected output: Lists of significantly differentially expressed genes (Supplementary Tables 3-22).
