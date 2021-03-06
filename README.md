# Analysis of prevalence of mental health disorders and calculating a mental health score

**Data used**
The dataset used in this analysis is a CSV file which records the presence/absence of various mental conditions among 279 patients enrolled in an observational study. The dataset has 256 variables, out of which some indicate presence/absence of mental conditions such as PTSD, depression, psychosis, bipolar disorder, panic disorder and anxiety. For each condition, there are details of further classification and medications taken for the condition. 

**Analysis**
There are 2 portions to this analysis: 
1. Descriptive analysis to calculate prevalence of the 6 conditions. 
2. Calculation of a mental health score for each patient

To execute the analysis, from the project folder you can run
Rscript -e "rmarkdown::render('HW4.Rmd')"
This will create a file called HW4.html output in your directory that contains the results.
