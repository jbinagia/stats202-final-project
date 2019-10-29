# Analyzing and Predicting Treatment Effects for Schizophrenia Patients (STATS 202 Final Project)
Authors: Jeremy Binagia & Sai Gourisankur 

In this repository contains the code used to complete the final project for Stanford STATS 202 in Summer 2019. Here, we analyzed a dataset containing statistics on a set patients diagnosed with schizophrenia. The main goals of this study were as follows: 
1. Given symptom severity (measured using the Positive and Negative Syndrome Scale, PANSS) as a function of time, can we conclude if there is a statistical significant difference between control and treatment groups (the latter being administered an anonymized drug). 
2. What characteristics define natural groupings (clusters) amongst the patients in the study? 
3. Can we forecast future symptom severity based on the available data? 
4. Because assigning PANSS scores is subject to human error, the patient assessments can be audited and flagged for review. Is it possible to automate the auditing process by building a model to determine a priori which assessments are likely to be flagged? 

We refer those interested to the [project prompt](https://github.com/jbinagia/stats202-final-project/blob/master/Prompt%20%26%20Writeup/final_project_prompt.pdf) as well as the [final project writeup](https://github.com/jbinagia/stats202-final-project/blob/master/Prompt%20%26%20Writeup/STATS_202_Final_Report.pdf) for further details of the project and of our analysis respectively. 

## Installation and Usage
- Install [R Studio](https://rstudio.com/) 
- Use [R Markdown](https://rmarkdown.rstudio.com/) to open up one of the four main notebooks. Each notebook corresponds to one of the four main goals above. These notebooks are as follows: 1) [treatment.Rmd](treatment.Rmd), 2) [segmentation.Rmd](segmentation.Rmd), 3) [forecasting.Rmd](forecasting.Rmd), and 4) [classification.Rmd](classification.Rmd). 
- While using R Markdown, click `Run` to view the results in R Studio or click `Knit`to convert the notebook to the desired format (Knitr supports conversion HTML, PDF, and Word although). Note that Knitr sometimes runs into issues during the conversion process, so we personally recommend using the former option or viewing the detailed [writeup](https://github.com/jbinagia/stats202-final-project/blob/master/Prompt%20%26%20Writeup/STATS_202_Final_Report.pdf) of our results. 
