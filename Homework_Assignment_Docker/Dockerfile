#Import the image from professor
FROM risserlin/bcb420-base-image:winter2024-arm64

#install additional packages

#install package from Bioconductor
RUN R -e 'BiocManager::install("DESeq2")'
RUN R -e 'BiocManager::install("enrichplot")'

#install package from CRAN
RUN R -e 'install.packages("pheatmap")'
