# MSDS-6306-case-study-1
SMU MSDS 6306 Doing Data Science- Case Study #1
Authors: Inderbir Dhillon (Project Lead), Jamie Vo, & Nick Blair

## Introduction

This document summarizes the analysis and findings centered around craft breweries and beers. The data contains 2000+ beers and 500+ breweries. The purpose of this analysis is to determine whether there are any findings that would be beneficial to the Budwiser enterprise, provide leadership (CEO and CFO of Budweiser) with data driven conclusions to make informed decisions, and/or allow for oversight on consumer preferences.

We appreciate you taking the time to review the within this repository below. Please contact Inderbir Dhillon (Project Lead), Nick Blair and/or Jamie Vo if you have any questions. 

## Analysis
1. Determine the number of breweries in each state. 
    1. Highest number of breweries (Colorado and California), Lowest number of breweries (North and South Dakota)
2. Address missing values.
    1. Removing records with missing values increased the minimum ABV from 0.1% to 2.7%
3. Determine median ABV and IBU.
    1. 5.6% and 39.98, repectively
4. Determine states with highest ABV adn IBU.
    1. 12.5% (Kentucky) and 138 (Oregon), respectively
5. Summary statistics findings.
    1. average ABV of 5.99%
6. Relationship between ABV and IBU.
    1. Strong, positive, linear relationship
7. Difference between IPAs and other Ales.
    1. IPAs have higher ABVs and IBUs
8. Additional findings.
    1. IPAs on the west coast have higher IBUs and are known for their hoppy nature

## Conclusion
We discovered that Colorado and California are the states with highest numbers of breweries (47 and 39 respectively). If we remove one of the two same breweries in Colorado, that number drops to 46. In addition to duplicates effecting the data, removing records that had missing values resulted in the minimum ABV to go from 0.1% to 2.7%. Since no other siginificant changes to the data summaries were observed, analysis continued with the removal of missing data. 

The median ABV and IBU were found to be 5.6% and 39.98, and the max to be 12.5% (Kentucky) and 138 (Oregon), respectively. Interestingly, we found a strong, positive linear relationship between ABV and IBU. After additional analysis, we can see that IPAs have a higher ABV and IBU than other ales, and by using a KNN algorithim, accuractely predict if its an IPA with 83% accuracy. In continuation of the Ale study, there is evidence to suggest that IPAs with higher IBUs are most prominent on the west coast. 

Additional data for analysis is recommended to support the findings found in this analysis. Regardless, it is interesting to observe high densities of breweries in Colorado and California. In addiiton, the data may suggest that higher ABV and IBU than average may flourish on the west coast (California) considering its prominence in the area. 


#### Sub-directories
/data - This directory contains the two data set files in .csv form and a Codebook file in text form which explains the details of the data sets.

#### Files
.gitignore - GitIgnore file to document unused files

Brewing.Rmd - RMarkdown file containing source code for this project

Brewing.nb.html - Knit file for this project

Cast Study 01 - Task Assignment.docx - Microsoft Word document providing the project instructions and scope

Case Study - Budweiser Brewery Insights.pptx - Microsoft PowerPoint slide deck containing presentation of findings from this project

README.md - This file.
