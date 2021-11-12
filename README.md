# mcctemplates

This is a package for storing RMarkdown templates that are suitable for use at the
Moffitt Cancer Center (https://www.moffitt.org/). In particular, the Biostatistics and Bioinformatics Shared Resource or BBSR can use this for analysis reports.

## Installing
To install this package, use
```
devtools::install_github("steveneschrich/mcctemplates")
```
Note there may be a few dependencies to install in addition, but that should happen automatically. 

## Using mcctemplates
It is very easy to use MCC templates in RStudio. Navigate to `File -> New File -> RMarkdown`
and scroll through to find the relevant template. That will open a template markdown that
you can then work from.

Note, if you use R by itself you can always perform the following:
```
dsreportr::new_markdown("mcctemplates::mcc_pdf")
```
That will create a new `Untitled.Rmd` in the current directory with the template.
