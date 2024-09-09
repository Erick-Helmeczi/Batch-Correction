# Batch Correction of Metabolomic Data

This interactive R Markdown document provides tools and summaries to help researchers identify and correct batch effects in metabolomic data usng quality control (QC) based batch correction algorithms. This document was designed to help users who have little to no experience reading or writing R script, and instead makes use of Shiny functionality for seamless optimization of correction models and exploration of results. Briefly, some of the tools provided in the document include customizable control charts, PCAs and data tables, which hep highlight the extent of batch effects prior to batch correcton, but also highlight the effectiveness of the correction algorithms used. Currently a few batch correction algorithms are available which can be optimized to fit the conditions of the study being processed. Lastly, tools to normalize (i.e. log transform, etc.) the corrected data, filter highly variable metabolites (i.e. technical CV threshold, etc.), and export the final results, are included in the final section of the R Markdown document. 

## Getting Started
### Data Format

This R Markdown document requires your data to be saved in a csv with the name "study matrix". Additionally, four columns are required to be placed before any metabolite data within this csv which include "id", "class", "batch", and "run_order". Following these four columns please include your metabolite data. Metabolite data must be complete (i.e. no missing value) and only contain numbers (cannot contain text outside of column headers for naming). Feel free use the "study matrix.csv" provided as a template. 

### Getting the Markdown File Up and Running

After downloading this repository, using the interactive R Markdown file is easy. Simply open the "Batch Correction.Rproj" file which will should open R Studio. Then open the file titled "Batch Correction Report.Rmd" and click "run document" in R Studio. The Markdown file will appear and you can now enjoy exploring your data.
