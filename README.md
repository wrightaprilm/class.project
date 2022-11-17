---
title: "README.Rmd"
author: "April Wright"
date: "`r Sys.Date()`"
output: html_document
---




```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Introduction
Enter a short description of your R Package.

+ What does it do? 
+ What type of data is it meant to work with? 
+ What are the major outputs of your R package? 

## Installation 

+ Are there any R packages yours depends on? 

```{r}
install.packages("tidyverse")
install.packages("phytools")
```

## Usage Examples

In this section, you want to provide some context for why someone might want to do whatever it is that your R package does. 

Multiplication is a fundamental mathematical operation and if a user wanted to do that in this packages, they would do:

```{r}
mult(5, 10)
```

