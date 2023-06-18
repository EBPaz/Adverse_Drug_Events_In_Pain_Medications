# project1
Repo for Data Class Project 1 (Eva Pazdera, Jenny Shin, Aleid van der Zel)

# Drug Adverse Events for Top Three Prescription Pain Medications
 
The industry selected by the analysis team was healthcare. Within the healthcare industry the team decided to focus on issues related to prescription medication as this would have direct patient impact. As the Food and Drug Administration has oversight over prescription mediation in the United States it was decided to use their open source API for data related to issues with prescrption drugs, also known as adverse events.

The purpose of this project is to understand the association of three top prescribed pain medications with drug adverse events to see if there are similarities in reactions, the seriousness of the events and the sex of the individuals affected. 

Fentanyl is a prescription pain medication currently popular for being abused in multiple ways. However, it is not the most commonly prescribed pain medication in its class. If we looked up adverse drug reactions, which includes drug abuse, through the Open FDA API, would the more commonly prescribed medications show equal abuse and or reactions?

## Questions
**1. How many adverse events and what types were reported?
Aleid

**2. How serious were the adverse events / number of serious events
    Almost three out of every four adverse reports for Hydrocodone, Oxycodone and Fentanyl were reported as serious.
In terms of seriousness, Fentanyl had the highest percentage of serious events (94%) in our dataset. Hydrocodone had 56.4% serious adverse events, which the least difference in serious vs non-serious. The Chi-square test result shows that there is statistical significance in the distribution of serious events for the three drugs.


**3. How many adverse events occurred in females vs. males?
     In general, more females than males reported adverse events from Hydrocodone, Oxycodone and Fentanyl combined. The drug with the largest spread between female and male reported adverse events is Hydrocodone, which shows almost 2/3 of the adverse events were reported by males. The drug with the least difference in number of reporters is Oxycodone. 

**4. When were the drug abuse reactions reported?
Aleid

## Link to Presentation
https://github.com/EBPaz/project1.git

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
