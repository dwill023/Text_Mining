# Text_Mining
This is an R Shiny app that displays PubMed articles that are text mined for diseases for potential treatments within queries related to immune pathways or indications. 

Pubmed articles were first queried with MeSH (Medical Subject Headings) terms related to pathways, cell types or functions related to a certain drug/small molecule's mechanism of action (MoA). Then those articles were tokenized and parsed using natural language processing (NLP) tools [tm](https://tm.r-forge.r-project.org/) and [tidytext](https://github.com/juliasilge/tidytext) in R. The data was then incorporated into this Shiny app to explore and visualize.

The Docker image is available [here](https://hub.docker.com/repository/docker/dwill023/tm-app).

The app is hosted [here](https://willdesi.shinyapps.io/Text_Mining/).
