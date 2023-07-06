# Fishnet 2 Data Migration Project

Author: Jeremy Holden 
Date: May 24, 2022  

The goal of this project is to document the workflow of migrating FN2 projects from the existing *DATA.ZIP* archive to a modern data product. The manual will outline tools for importing, cleaning and outputting a project or series of projects.

## View the book online
https://fishnetmigration.github.io/FN2DataMigrationManual/

## Render book

You can render the HTML version of this book locally:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:

```{r, eval=FALSE}
bookdown::render_book()
```



```{r include=FALSE}
# automatically create a bib database for R packages
knitr::write_bib(c(
  .packages(), 'bookdown', 'knitr', 'rmarkdown', 'usethis', 'gfsR', 'rprocval'
), 'packages.bib')
```

