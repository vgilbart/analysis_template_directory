# Analysis Template Directory

This is a template directory for analysis projects.

## Folder description 

- data: contains raw data (or symbolic links to raw data)
- doc: contains related studies
- result:   
    * figure: contains figure results generated from scripts
    * table: contains table results generated from scripts
- script: contains scripts to generate results

## R analysis projects

If you are analysing with R, you should work inside a [Rproject](https://support.posit.co/hc/en-us/articles/200526207-Using-RStudio-Projects). To do this, manually create a file named `$NAMEOFPROJECT.Rproj`, or create a new project with the GUI of RStudio. 

When opening the Rproject in RStudio you should, run `renv::init()` to create [renv](https://rstudio.github.io/renv/articles/renv.html).

You can also add a `result/rds` folder that will contain some important RDS objects created during the analysis.
