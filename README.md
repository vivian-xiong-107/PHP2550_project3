# PHP2550 project3


Comparative Analysis of Simulated vs. Non-Simulated Transportability


Caiwei Xiong 

## Abstract 

**Background:** Risk prediction models, like the Framingham ATP-III model for cardiovascular disease, play a pivotal role in clinical decision-making. However, their effectiveness can be compromised when applied to populations with distinct characteristics. To address this, transportability analysis techniques have been developed to fine-tune model performance to account for demographic differences. Yet, these techniques often depend on individual-level data from the target population, which may not always be accessible. In this context, simulating target population data using summary statistics emerges as a potential solution to this challenge.


**Methods:** Using summary statistics from the National Health and Nutrition Examination Survey (`NHANES`) and a range of correlation parameters, we generated data for a simulated target population. We then conducted transportability analyses on each dataset to calculate the model's Brier score and Area Under the Curve (AUC). For each correlation scenario, we compared the bias of these estimates against the Brier score and AUC derived from individual-level NHANES data.


**Results:** In our transportability analyses, which utilized simulated datasets, we observed relative biases ranging from -0.05 to 1.5 when compared to estimates obtained from individual-level data. Adjustments in the degree of association between specific simulated variables indicated potential for performance improvement. However, it's noteworthy that simulations assuming no associations did not show substantial differences. This finding suggests that the assumed inter-variable associations may have a limited impact on the accuracy of our transportability analyses.


**Conclusions:** The observation of low relative biases in our study supports the validity of using simulated data for transportability analysis, particularly in estimating Brier scores and Area Under the Curve (AUC) for a target population when individual-level data is unavailable. Furthermore, our findings indicate that researchers can simplify the process of simulating target data by assuming no association between covariates, without significantly compromising the accuracy of the results. This approach could offer a more straightforward and accessible method for conducting such analyses.

## Dataset

The `NHANES` package, offers a comprehensive collection of data pertaining to blood pressure measurements. This dataset is instrumental in understanding various health aspects related to blood pressure across a diverse population. It encompasses a wide range of variables, including systolic and diastolic blood pressure readings, which are crucial for medical research and public health analysis. The data, derived from a nationally representative sample, provides insights into the prevalence and distribution of blood pressure-related health conditions in the U.S. population. The NHANES survey's rigorous methodology ensures the reliability and accuracy of dataset, making it a valuable resource for epidemiologists, public health officials, and researchers in related fields.




The `Framingham` dataset, accessible through the `RiskCommunicator` package, originates from the renowned Framingham Heart Study. This dataset is pivotal in cardiovascular research, offering extensive data on risk factors associated with heart disease. It includes a variety of variables such as cholesterol levels, blood pressure, diabetes status, smoking habits, and other relevant health indicators. The dataset's longitudinal design, tracking participants over an extended period, allows for in-depth analysis of cardiovascular disease progression and risk factor evolution. The Framingham study's contribution through this dataset has been instrumental in shaping our understanding of heart disease, influencing preventive measures and treatment strategies worldwide. The dataset's comprehensive nature and historical significance make it a cornerstone in the field of cardiovascular research and risk assessment.


## Packages

All code contained within the R Markdown (Rmd) file is compatible with R version 4.2.1 and can be successfully compiled. The following part lists the packages and their corresponding versions that will be used:

nhanesA (0.7.4)

riskCommunicator (1.0.1)

tidyverse (1.3.2)

tableone (0.13.2)

caret (6.0-94)

knitr (1.39)

dplyr (1.1.3)

kableExtra (1.3.4)

gtsummary (1.7.2)

ggplot2 (3.4.0)

gt (0.9.0)

MASS (7.3-58.1)



## Files

The codes for the codes for construct report was stored in: `proejct3.Rmd` 

## Acknowledgement

This project represents a collaborative effort, involving Dr. Jon Steingrimsson in the Biostatistics Department (jon_steingrimsson@brown.edu), and is under the guidance of Dr. Alice Paul (alice_paul@brown.edu).

