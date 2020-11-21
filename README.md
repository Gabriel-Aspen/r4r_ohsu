# Ready for R - course notes
Taught by Dr. Ted Laderas  
Medical Informatics and Clinical Epidemiology  
Oregon Health & Science University  
Link: [Ready for R](https://ready4r.netlify.app/)  

## Learning Objectives
1. Understand and utilize R/RStudio.
2. Understand basic data types and data structures in R.
3. Familiarize and load data files (Excel, Comma Separated Value files) into R/Rstudio, with tips on formatting.
4. Visualize datasets using ggplot2 and understand how to build basic plots using ggplot2 syntax.
5. Filter and format data in R for use with various routines.
6. Execute and Interpret some basic statistics in R.

## Libraries:
### Base R
- t.test()
### tidyverse
- **ggplot2**: Plotting data with ggplot(), aes() and:
  - geom_jitter()
  - geom_boxplot()
  - geom_point()
  - + geom_smooth(): method = 'lm' for linear models
- **dplyr**: Data manipulation
- **readxl**: read Excel/csv
- **forcats**
### janitor
- **tabyl**
###tidymodels
- broom
  - tidy(): can show coefficients and p-values. Use in conjunction with lm()
  - glance(): additional measures on your model (R-squared, log likelihood, and AIC/BIC)
  - augment() - make predictions with your model using new data
### GGally: Extends ggplot
- ggpairs(): Pairplot
### readxl:
