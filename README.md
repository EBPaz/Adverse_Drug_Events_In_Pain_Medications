# project1
Repo for Data Class Project 1 (Eva Pazdera, Jenny Shin, Aleid van der Zel)

# Adverse Drug Events for Top Three Prescription Pain Medications
 
The industry selected by the analysis team was healthcare. Within the healthcare industry, the team decided to focus on issues related to prescription medication as this would have direct patient impact. As the Food and Drug Administration has oversight over prescription medication in the United States, it was decided to use their open source API for data related to issues with prescription drugs, also known as adverse events.

The purpose of this project is to understand the association of three top prescribed pain medications with drug adverse events to see if there are similarities in reactions, the seriousness of the events and the sex of the individuals affected. 

Fentanyl is a prescription pain medication currently popular for being abused in multiple ways. However, it is not the most commonly prescribed pain medication in its class. If we looked up adverse drug reactions, which includes drug abuse, through the Open FDA API, would the more commonly prescribed medications show equal abuse and or reactions?

## Questions
**1. How many adverse events and what types were reported?**  
In the first quarter of 2023 there were a total of 641 recorded in 49 categories. Drug abuse had the largest number of events attributed to fentanyl and mostly reported on one day. The next highest events were death and completed suicide both associated with hydrocodone.

**2. How serious were the adverse events / number of serious events**  
Almost three out of every four adverse reports for Hydrocodone, Oxycodone and Fentanyl were reported as serious. Fentanyl had the highest percentage of serious events (94%) in our dataset. Hydrocodone had 56.4% serious adverse events, which had the least difference in serious vs non-serious. The Chi-square test result shows that there is statistical significance in the distribution of serious events for the three drugs.

**3. How many adverse events occurred in females vs. males?**  
In general, more females than males reported adverse events from Hydrocodone, Oxycodone and Fentanyl combined. The drug with the largest spread between female and male reported adverse events is Hydrocodone, which shows almost 2/3 of the adverse events were reported by males. The drug with the least difference in number of reporters is Oxycodone. 

**4. When were the drug abuse reactions reported?**  
Most drug abuse reactions were reported in January of this year with a spike on January 13

## Conclusion
How many/type of events:  
In the first quarter of 2023 there were a total of 641 recorded in 49 categories. Drug abuse had the largest number of events attributed to fentanyl and mostly reported on one day. The next highest events were death and completed suicide both associated with hydrocodone.  

Severity of events:  
There were 472 serious events for the three drugs. 94% of the adverse events reported for Fentanyl were serious.  

Distribution male/female:  
More females than males experience adverse events from Hydrocodone, Oxycodone and Fentanyl combined. However, we don’t know if that is due to actual experience or frequency of reporting.  

We met the intent of the project with a few lessons:
Understanding the data source/API is important and time consuming  
Over the timeframe evaluated there were more adverse events reported for fentanyl than the other two drugs and 94% of the events were serious  
Answering one question opens the door to many more….  

## Link to Presentation
https://drive.google.com/file/d/1ohToQL94SSVmVThD417hKoJhIcq7Z9NA/view 


## Installing
The following applications are necessary to manage and clean the data for our questions.  
import pandas as pd  
import requests  
import json  
import numpy as np  
import matplotlib.pyplot as plt  
import scipy.stats as stats  
from scipy import stats  

## Sources
https://open.fda.gov/  
Shout out to: Ryan Coble and Andrew Krieger!

## Contributing
Eva Pazdera, Jenny Shin, Aleid van der Zel
