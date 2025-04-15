
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Brand Perception Mapping with Correspondence Analysis

This project was conducted for a survey software company (Brand C) to
evaluate its market position relative to four competitors. Using
perception data from over 5,000 survey respondents, we explored how each
brand is associated with key product attributes.

## Goals

- Map consumer perceptions of Brand C vs. competitors
- Identify Brand C’s strengths and weaknesses across 8 core attributes
- Recommend strategic actions based on perceptual insights
- Validate attribute-brand relationships statistically

## Methods & Tools

R, RMarkdown, RStudio tidyverse, FactoMineR, factoextra, vcd, ca,
CAinterprTools, plotly, ggplot2, ggpubr, ggforce, ggrepel, lubridate,
DT, flextable, sjlabelled

## Analytic Approach:

Data Cleaning, Descriptive Insights, Correspondence Analysis, Malinvaud’s
Test for optimal dimension retention, Mosaic Plots to validate
brand-attribute associations

## Data
4,102 initial respondents & 3,809 after filtering
for quality and response time; Respondents rated 5 brands across 8
product attributes

## Key Findings

- Two dimensions captured 96.6% of the variation in brand-attribute
  relationships.
- Brand C was associated most with: Data Analysis, Data Security, &
  Integration
- Brand E was dominant and strongly associated with ease and
  collaboration.
- Brands B and D were viewed as cost-effective solutions.

## Visual Outputs

Perceptual Maps Mosaic Plots with Friendly shading, Balloon Plot to
visualize attribute frequency by brand, Kernel Density Plots for response
time (speeding detection) & Chi-Square Test of Independence

## How to Run

- Place my_brand_data in your working directory.
- Open the .Rmd file in RStudio.
- Install the required packages: if (!require(“pacman”))
install.packages(“pacman”) pacman::p_load(haven, ggplot2, dplyr, plotly,
flextable, sjlabelled, FactoMineR, factoextra, vcd, chisq.posthoc.test,
anacor, ca, tibble, gplots, ggpubr, qcc, CAinterprTools, rgl, corrplot,
lubridate, DT, ggforce, ggrepel)
- Knit the .Rmd file to view the final
report in HTML format.
- Custom css file for rendering the html page 
