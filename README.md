# RES Reproducibility Template Repository

![](banner.png)

> This repo is the template for reproducibility checks at the Royal Economic Society Journals.

## How to use this template

1. Create a new repository using this template. You can do this by clicking the green "Use this template" button on the top right of this page.
2. Open RStudio and create a new project from version control. Select "Git" and paste the URL of the repository you just created.

## Which Template to use?

1. You can directly edit the source file (`.qmd`), which is in *quarto* format in Rstudio. Basically markdown. In that case dit the `EJ-report.qmd` file in RStudio. click on *render* to see the current output.
2. You can edit the corresponding `.docx` file in MS Word if you prefer
3. You can edit the corresponding `.odt` file in OpenOffice if you prefer


### Meta

one creates the `.docx` and `.odt` on the quarto command line with

```
quarto render EJ-report.qmd --to odt,html,docx
```