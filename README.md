# Basics of R Programming

R is a powerful programming language and software environment widely used for statistical analysis, data visualization, and machine learning. It provides a vast array of tools and libraries that make it a popular choice among data scientists, statisticians, and researchers.

R excels in statistical analysis and is equipped with a rich set of functions for descriptive statistics, hypothesis testing, regression analysis, time series analysis, and multivariate techniques. This makes it a preferred choice for researchers and analysts working with data from various fields, such as social sciences, finance, healthcare, and environmental studies.

Moreover, R offers exceptional data visualization capabilities. Its default plotting system allows users to create a wide variety of static and interactive visualizations to explore and present data effectively. Additionally, packages like [`ggplot2`](https://ggplot2.tidyverse.org/) provide a grammar of graphics approach, enabling users to construct complex and customizable plots with ease.

In recent years, R has gained popularity in the field of machine learning. Packages such as [`caret`](https://topepo.github.io/caret/), [`randomForest`](https://www.rdocumentation.org/packages/randomForest/versions/4.7-1.2), and [`keras`](https://cran.r-project.org/web/packages/keras/vignettes/) offer powerful tools for building and evaluating predictive models. R's integration with other languages, such as Python, allows users to leverage popular machine learning frameworks like TensorFlow and scikit-learn within their R workflow.

## 📢 Before Starting

1. Download and install both **R** and **RStudio**: https://posit.co/download/rstudio-desktop/
1. This tutorial uses R markdown files. Kindly refer to this video on how to work with R markdown files on RStudio: https://www.youtube.com/watch?v=DNS7i2m4sB0
1. Download this [file](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/phages.tsv) (`phages.tsv`), and place it inside the same folder as the R markdown files that you will be creating in this tutorial.

## 📜 Topic Outline

**R markdown** files (second column) can be directly opened and run on RStudio. However, when opened on GitHub, only the raw code is displayed and outputs (e.g., tables and plots) are stripped.

**GitHub markdown** files (third column) cannot be directly opened and run on RStudio. However, GitHub displays them nicely while also preserving the outputs.

\# | Topic | R Markdown | GitHub Markdown
-- | -- | -- | --
1 | Introduction to R Syntax | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/1.%20Introduction%20to%20R%20Syntax.Rmd)
2 | Groups of Data: Vectors, Matrices & Lists | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/2.%20Groups%20of%20Data%20-%20Vectors%2C%20Matrices%20%26%20Lists.Rmd)
3 | Learn R: Data Frames | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/3.%20Learn%20R%20-%20Dataframes.Rmd)
4 | Manipulating Data with `dplyr` | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/4.%20Manipulating%20Data%20with%20dplyr.Rmd)
5 | Learn R: Fundamentals of Data Visualization with `ggplot2` | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/5.%20Learn%20R%20-%20Fundamentals%20of%20Data%20Visualization%20with%20ggplot2.Rmd)
6 | Descriptive Statistics | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/6.%20Descriptive%20Statistics.Rmd)
7 | Inferential Statistics | [Link](https://github.com/bioinfodlsu/basic-r-tutorial/blob/main/7.%20Inferential%20Statistics.Rmd)

## 📚 References

This tutorial references the following resources:
- https://www.kaggle.com/code/hamelg/intro-to-r-index/notebook
- https://uclouvain-cbio.github.io/WSBIM1207/sec-dplyr.html

The dataset we use in this tutorial was downloaded using [INPHARED](http://doi.org/10.1089/phage.2021.0007) last September 2022:
- Cook, R., Brown, N., Redgwell, T., Rihtman, B., Barnes, M., Clokie, M., Stekel, D. J., Hobman, J. L., Jones, M. A., & Millard, A. (2021). INfrastructure for a PHAge REference Database: Identification of large-scale biases in the current collection of cultured phage genomes. _PHAGE, 2_(4), 214-223. http://doi.org/10.1089/phage.2021.0007

## 💻 Authors

- **Daphne Janelyn L. Go** <br>
  daphne_janelyn_go@dlsu.edu.ph
  
- **Mark Edward M. Gonzales** <br>
  mark_gonzales@dlsu.edu.ph

These materials were originally created for the **Basic R Workshop**, jointly organized by the [Bioinformatics Lab](https://bioinfodlsu.com/) with the [Systems and Computational Biology Unit](https://dlsu-scomb.github.io/), De La Salle University, last July 12, 2023.
