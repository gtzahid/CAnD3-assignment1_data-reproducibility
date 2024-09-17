# CAnD3-assignment1_data-reproducibility
## README File: CAnD3-assignment1_data-reproducibility
### Practicing Replicability and Reproducibility
  
## Assignment Description
This assignment is part of a CAnd3 exercise and examines the relationships between age, sex and marital status. I use the 2016 General Social Survey for a linear regression analysis. Below, information is included about how to use the 
files provided to reproduce the analyses leading to this conclusion.

***

## Data Description

***

### Data Source Availabiliy Statement
Data come from the 2017 (cycle 31) Canadian General Social Survey. These data 
are made available through [ODESI](https://search1.odesi.ca/#/), a service 
provided by the Ontario Council of University Libraries. Access is restricted 
to those users who have a DLI License and can be used for statistical and 
research purposes. The terms of the license can be viewed [here](https://www.statcan.gc.ca/eng/dli/licence).  

As part of McGill University, the CAND3 initiative has a license to use the data 
for the purposes of training. Those outside of McGill university should not use 
the data provided through CAND3's training activities for purposes not related 
to their CAND3 training. Trainees who belong to another DLI institution should 
re-download the data using the ODESI site using the login provided by their 
institution if they wish to make use of the data for other purposes.  

**CODEBOOK AND SUMMARY STATISTICS**  
The codebook and summary statistics for these data are publicly available [here](http://odesi1.scholarsportal.info/documentation/GSS31/c31pumf_families_codebook_E.pdf).  
  
**CITATIONS**  
Statistics Canada. 2020. General Social Survey, Cycle 31, 2017 [Canada]: Family (version 2020-09). Statistics Canada [producer and distributor], accessed September 11, 2024. 

***

### Files Included

**File Name**             | **Purpose**
--------------------------| -------------------------------------------------
'RRWM_GZ.Rmd'             | Calls Scripts to Conduct All Analyses
'RRWM_GZ-read'            | PDF version of the program


***
**Please note that I have read the CSV after downloading the data onto my desktop. Replicators should change file path based on where they are accessing the data from.** 

### Instructions for Data Preparation and Analysis
To reproduce the analyses conducted here, download the zip file of this project. 
The zip file will create the folder "CAnD3-Data-Activity." This folder will be 
your working directory. Once you obtain access to the dataset, rename it 
"gss_2017.csv" and save it in the working directory (CAnD3-Data-Activity). Open and 
run (knit) the shell file ('Shell File.Rmd'). This file calls on the individual 
script files to clean the data, manage missing data, and produce the descriptive 
and regression tables.  

***

## Computational Requirements

***

### Software Requirements
The following software programs are required to reproduce these analyses:  

* R and Rstudio (version 1.4.4) and the following packages as of 9/17/24
    + tidyverse  
    + dplyr  
    + tibble 
    + broom    

***

### Machine Information
These analyses were conducted using Windows 11 version 23H2:  

* 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 2.70 GHz Processor
* 8 GB 1600 MHz DDR3 Memory

