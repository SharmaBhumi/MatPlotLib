# The Power of Plots

## Pymaceuticals Inc

![Laboratory](Images/pharma_image2.png) ![Laboratory](Images/pharma_image.png)


### Datails for Data:
Pymaceuticals Inc.specializes in drug-based, anti-cancer pharmaceuticals. They are screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. 

Data is analyzed to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

To do this following is done:

* A Scatter plot is created that shows how the tumor volume changes over time for each treatment.
* A Scatter plot is created that shows how the number of [metastatic](https://en.wikipedia.org/wiki/Metastasis) (cancer spreading) sites changes over time for each treatment.
* A Scatter plot is created that shows the number of mice still alive through the course of treatment (Survival Rate)
* A bar graph is created that compares the total % tumor volume change for each drug across the full 45 days.

## Libraries and Tools used:
-	Pandas & Matplotlib Library 
-	Jupyter Notebook


### The data suggests the following:

**Drug effects analysis for Tumor Volume:**

Drug Capomulin seems to be the most effective in reducing the total Tumor volume during the 45 days of treatment.It reduced 
the Tumor volume by 19%.Drugs Infubinol and Ketapril were not effective in reducing the Tumor volume,rather the total Tumor 
volume increased by 46% and 57% respectively during the treatment.If Tumor volume growth in case of Placebo is considered 
as a normal growth then Infubinol seems to reduce the growth rate.It's testing duration can be increased to see if the 
growth reduction continues.Infubinol regime seem to have slowed the Tumor growth but the Survival rate suddenly dropped 
from almost 70% to less than 50% after Day 30 of treatment.This is evident from the Survival Rate Scatter Plot as well. 

**Metastatic Spread During treatment using various Drug regimes:**

Cancer is metastasizing during the treatment duartion for all the Drugs but spread sites are less in the case of Drug 
Capomulin.Metastatic sites seems to be stabilising between Day 40 and 45 for Drug Infubinol at 2.1 sites.This trend can 
be studied for longer duration to see if it continues or worsens.

**Conclusion:**

Evidence like, Reduction in Tumor Volume by 19%,Survival Rate >80%,Metastatic Spread sites<=1.5 during the 45 Days of 
treatment shows that Capomulin drug regime is most effective.If this Drug regime can be tested on more samples and 
for a longer duration then more precise conclusions can be driven.
