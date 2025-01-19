# Basics of R Programming

R is a powerful programming language and software environment widely used for statistical analysis, data visualization, and machine learning. It provides a vast array of tools and libraries that make it a popular choice among data scientists, statisticians, and researchers.

R excels in statistical analysis and is equipped with a rich set of functions for descriptive statistics, hypothesis testing, regression analysis, time series analysis, and multivariate techniques. This makes it a preferred choice for researchers and analysts working with data from various fields, such as social sciences, finance, healthcare, and environmental studies.

Moreover, R offers exceptional data visualization capabilities. Its default plotting system allows users to create a wide variety of static and interactive visualizations to explore and present data effectively. Additionally, packages like [`ggplot2`](https://ggplot2.tidyverse.org/) provide a grammar of graphics approach, enabling users to construct complex and customizable plots with ease.

In recent years, R has gained popularity in the field of machine learning. Packages such as [`caret`](https://topepo.github.io/caret/), [`randomForest`](https://www.rdocumentation.org/packages/randomForest/versions/4.7-1.2), and [`keras`](https://cran.r-project.org/web/packages/keras/vignettes/) offer powerful tools for building and evaluating predictive models. R's integration with other languages, such as Python, allows users to leverage popular machine learning frameworks like TensorFlow and scikit-learn within their R workflow.

## Before Starting

### 1. Install the required software
Download and install both **R** and **RStudio**: https://posit.co/download/rstudio-desktop/

This tutorial consists of R markdown files. Kindly refer to this video on how to work with R markdown files on RStudio: https://www.youtube.com/watch?v=DNS7i2m4sB0

### 2. Create a copy of this repository
If you have [Git](https://git-scm.com/) installed, run the following command on the terminal:
```
git clone https://github.com/bioinfodlsu/basic-r-tutorial
```

If Git is not installed, click the green `Code` button near the top right of the repository and choose `Download ZIP`. Once the zipped folder has been downloaded, extract its contents.

## Topic Outline

- [Introduction to R Syntax](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/1.%20Introduction%20to%20R%20Syntax.Rmd)
- [Groups of Data: Vectors, Matrices & Lists](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/2.%20Groups%20of%20Data%20-%20Vectors%2C%20Matrices%20%26%20Lists.Rmd)
- Learn R: Data Frames
- Manipulating Data with `dplyr`
- Learn R: Fundamentals of Data Visualization with `ggplot2`
- Descriptive Statistics
- Inferential Statistics

## References

The notebooks reference the following tutorials:
- https://www.kaggle.com/code/hamelg/intro-to-r-index/notebook
- https://uclouvain-cbio.github.io/WSBIM1207/sec-dplyr.html

The dataset used was downloaded using [INPHARED](http://doi.org/10.1089/phage.2021.0007) last September 2022:
- Cook, R., Brown, N., Redgwell, T., Rihtman, B., Barnes, M., Clokie, M., Stekel, D. J., Hobman, J. L., Jones, M. A., Millard, A. (2021). INfrastructure for a PHAge REference Database: Identification of large-scale biases in the current collection of cultured phage genomes. _PHAGE,2_(4), 214-223. http://doi.org/10.1089/phage.2021.0007

## Authors

- **Daphne Janelyn L. Go** <br>
  daphne_janelyn_go@dlsu.edu.ph
  
- **Mark Edward M. Gonzales** <br>
  mark_gonzales@dlsu.edu.ph

These materials were originally created for the **Basic R Workshop**, jointly organized by the [Bioinformatics Lab](https://bioinfodlsu.com/) with the [Systems and Computational Biology Unit](https://dlsu-scomb.github.io/), De La Salle University, last July 12, 2023.
