
To reproduce the results, follow these steps:

1. Download the contents of the GitHub repository.

2. Open a new R session.

3. Set the working directory to the downloaded GitHub repository

4. run the following commands:
  install.packages("renv")
  renv::restore()
  rmarkdown::render("PRC_analysis.Rmd")
  
  