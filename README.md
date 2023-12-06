# PHP2550 project3


Comparative Analysis of Simulated vs. Non-Simulated Transportability


Caiwei Xiong 

## Abstract 

**Background:** Transportability analyses are designed to extend inferences from a specific source population to a distinct target demographic. These analyses are crucial for decision-makers, as they leverage findings from controlled trials to estimate the anticipated average benefit within a real-world population. This process employs advanced statistical methods to reconcile differences between populations, ensuring that the derived conclusions are pertinent and accurately represent the potential outcomes within the target group.


**Methods:** 


**Results:**


**Conclusions:**
In this report, we trained a logistic regression model using data from the `Framingham` study (source dataset) and subsequently applied this model to both non-nested datasets. (i.e., the `NHANES` dataset and a `simulated` dataset). Our findings reveal that the simulated dataset achieved a more favorable Brier score compared to the NHANES dataset. This suggests that the simulated dataset more closely resembles the Framingham study in terms of essential characteristics or risk factor profiles. Such insights are invaluable for future endeavors in model development and refinement, underscoring the need for predictive models that are not only precise in their original context but also retain their accuracy and applicability across diverse population groups.

## Dataset

The `NHANES` (National Health and Nutrition Examination Survey) package, offers a comprehensive collection of data pertaining to blood pressure measurements. This dataset is instrumental in understanding various health aspects related to blood pressure across a diverse population. It encompasses a wide range of variables, including systolic and diastolic blood pressure readings, which are crucial for medical research and public health analysis. The data, derived from a nationally representative sample, provides insights into the prevalence and distribution of blood pressure-related health conditions in the U.S. population. The NHANES survey's rigorous methodology ensures the reliability and accuracy of dataset, making it a valuable resource for epidemiologists, public health officials, and researchers in related fields.




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

This project represents a collaborative effort, involving Dr. Jon Steingrimsson in the Biostatistics Department (jon_steingrimsson@brown.edu), and is under the guidance of Dr. Alice Paul (alice_paul@brown.edu)."

