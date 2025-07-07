This repository contains the data and code associated with the abstract "*A Funder-Led Intervention to Increase the Sharing of Data, Code, Protocols, and Key Laboratory Materials*", which will be published as part of the Peer Review Congress 2025 (https://peerreviewcongress.org/).

Correspondence should be directed to openscience@parkinsonsroadmap.org

### Reproducibility

To reproduce the results, follow these steps:

1. Download the contents of the GitHub repository.

2. Open a new R session.

3. Set the working directory to the downloaded GitHub repository

4. Run the following commands:  
  install.packages("renv")  
  renv::restore()  
  rmarkdown::render("PRC_analysis.Rmd")

### Data

- Input data are in the /data folder.  
- Results are in the /results folder.
- Codebooks describing each variable from the data and results are in the /codebooks folder.
- A list of DOIs for all publications is provided in data/df_preprint_dates.csv
- The first versions of the manuscripts cannot be made publicly available because they are based on manuscript drafts that grantees privately shared with ASAP staff. 
  