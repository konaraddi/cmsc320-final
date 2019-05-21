# cmsc320-final

CMSC320 Final Project Submission

## Getting Started

Requirements: R and RStudio

To run individual `.Rmd` files, you'll first need to run the `scraping.Rmd` file since it prepares variables that you'll need in your global environment to run the other files

## Building the HTML report

Include all necessary `.Rmd` files in the `index.Rmd` file (look at the file to see how it's done). Build the report by copying and pasting the following command in the Console of RStudio

```r
rmarkdown::render('index.Rmd')
```

You may need to the set the working directory to the project folder for this to work

## Authors

Dinakar Chappa, Prashant Krishnan, Omkar Konaraddi
