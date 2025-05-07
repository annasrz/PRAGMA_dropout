# Predictors of irregular discontinuation of alcohol-specific addiction treatments 

This repository contains R scripts used in the statistical analyses for the study:
"Predictors of irregular discontinuation of alcohol-specific addiction treatments"

## Study Overview

### Background:
This study investigates treatment discontinuation among people with alcohol use disorders using routine data from two German statutory health insurance funds (AOK and DAK). The objective was to identify sociodemographic and health-related predictors for the irregular discontinuation of alcohol-specific treatments.

### Methods:
Retrospective analyses were conducted for insured adults (18+) residing in Hamburg who underwent at least one of the following treatments between 2016 and 2021:

    SAB (inpatient alcohol treatment): n = 1,779 individuals, 3,811 episodes

    QEB (qualified withdrawal treatment): n = 1,911 individuals, 3,758 episodes

    REHA (medical rehabilitation): n = 550 individuals, 672 episodes

Hierarchical logistic regression models were used to identify predictors of irregular treatment discontinuation.

Key Predictors:

    Sociodemographics (sex, age, employment status, nationality)

    Health-related variables (comorbidities, medication, care status)

    Treatment history (number of previous treatment episodes)

## Repository Structure

This repository includes one R script per treatment type:

    SAB_analysis.Rmd — Analysis of inpatient alcohol treatment episodes

    QEB_analysis.Rmd — Analysis of qualified withdrawal treatment episodes

    REHA_analysis.Rmd — Analysis of medical rehabilitation treatment episodes

Each script performs data preprocessing, model fitting (glmmTMB), and results output.



This analysis is part of the projekt "Analyse von Patient:innenwegen von Menschen mit einer Alkoholabhängigkeit in Deutschland (PRAGMA)“
