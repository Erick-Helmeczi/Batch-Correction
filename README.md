# Batch-Correction

This interactive R Markdown document provides tools and summaries to help students, researchers, and technicians identify batch effects in their metabolomic data sets, optimize appropriate batch correction algorithms, and export corrected matrices.

## Getting Started
### Data Format

This R Markdown document requires your data to be saved in a csv with the name "study matrix". Additionally, four columns are required to be placed before any metabolite data within this csv which include "id", "class", "batch", and "run_order". Following these four columns please include your metabolite data. Metabolite data must be complete (i.e. no missing value) and only contain numbers (cannot contain text outside of column headers for naming). Feel free use the "study matrix.csv" provided as a template. 

### Getting the Markdown File Up and Running

After downloading this repository, using the interactive R Markdown file is easy. Simply open the "Batch Correction.Rproj" file which will should open R Studio. Then click "run document" and the Markdown file will appear. You can now enjoy exploring your data with the help of the section summaries provided in the document. 
