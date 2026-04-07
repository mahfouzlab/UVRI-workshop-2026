# Data Without Borders: UVRI Multiomics Integration Workshop
_A Practical Guide for Bench Scientists Moving into Computational Analysis_ 

## Schedule
You can find the detailed schedule of the workshop with links to lecture slides and practical notebooks [here](schedule.md).

## Workshop Description
# Who Is This Workshop For?
This workshop is designed for researchers who:
- Have been doing experimental immunology/biology work and now have multi-omics data to analyze
- Have basic R skills (can use tidyverse, make ggplots) but feel overwhelmed by analysis options
- Need practical workflows they can adapt to their own datasets and thesis/publications
- Want to understand not just how to run analyses, but when and why to choose specific methods
- Learn best through hands-on exercises with clear, step-by-step guidance

# What You'll Walk Away With
By the end of this workshop, you will have:
- A clear mental framework for choosing between analysis methods
- Working R code templates you can adapt for your own data
- Confidence to interpret results and explain them in papers/presentations
- Troubleshooting skills for common problems
- Publication-quality figures from your analyses

# What This Workshop is not About
The following points are important elements of multi-omics analysis but beyond the scope of the course:
- Data-specific quality control and normalization
- Feature engineering (turning raw data into variables that statistical models can use, e.g. pathway activity levels)
- Diagnosing and correcting batch effects
- Integrative analysis for multiple data/studies (e.g. meta analysis)

# Case Study
We'll learn by reproducing key analyses from: [Manurung et al. (2025)](https://doi.org/10.1126/sciadv.adu0419) "Systems analysis unravels a common rural-urban gradient in immunological profile, function, and metabolic dependencies" — Science Advances

This paper integrates five datasets from rural and urban populations to identify immune signatures. You'll recreate their main figures while learning transferable skills for your own research.

# Prerequisites Checklist
Before the workshop, confirm you can:
- Open RStudio and create a new R script
- Install packages with `install.packages("tidyverse")`
- Load data with `read.csv()`
- Do basic data manipulation (`filter()`, `select()`, `mutate()`)
- Create a simple ggplot (`ggplot() + geom_point()`)
- Run a simple linear model (`lm(y ~ x, data = df)`)
- Load data with `read.csv()`
- Do basic data manipulation (`filter()`, `select()`, `mutate()`)
- Create a simple ggplot (`ggplot() + geom_point()`)
- Run a simple linear model (`lm(y ~ x, data = df)`)

You don't need to know:
- How to write custom functions
- The mathematics behind the methods
- Any prior experience with omics-specific packages

# Workshop Materials
All code, data, and templates will be provided via this GitHub repository. Each session includes:
📋 Step-by-step code with extensive comments
🔧 Troubleshooting guides for common errors
📝 Template scripts you can adapt for your own data

