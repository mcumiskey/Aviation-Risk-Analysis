
![](images/horizontal_div_right.png)
# Aviation-Risk-Analysis
Created for the August 2024 Flatiron Data Science Cohort. A collection of insights for a company looking to break into the public and private aviation buisness, focusing on determining which models had the least injuries and fatalities in event of a crash. 

## Authors
Miles Cumiskey: https://github.com/mcumiskey

Joey Barilla: https://github.com/JoeyBarlia

![](images/horizontal_div_left.png)

# Overview
Presentation: https://github.com/mcumiskey/Aviation-Risk-Analysis/blob/main/Presentations/Phase%201_%20Aviation%20Project.pdf

Tableau: https://public.tableau.com/views/Aviation_Project_17242489618110/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Structure 
```
├── Presentations
│   ├── notebook.pdf
│   ├── github.pdf
│   └── Phase_1_Aviation Project.pdf
├── data
│   ├── AviationData.csv
│   └── USState_Codes.csv
├── images
│   ├── airplane-isolated-on-transparent-background-3d-rendering-aircraft-png-2455088391.png
│   ├── horizontal_div_left.png
│   └── horizontal_div_right.png
├── .DS_Store
├── .gitignore
├── README.md
└── aviation analysis conclusion.ipynb
```
## Business Understanding
A company is interested in purchasing and operating airplanes for commercial and private enterprises, but they do not know anything about the potential risks of aircraft. 

Our goal is to determine which aircraft are the lowest risk for the company through analysis of the aeroplane's fatality and injury rates in event of a crash. 

## Data Understanding and Analysis
(https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses?resource=download)

The data is from the National Transportation Safety Board. It includes aviation accident data from 1962 to 2023 about civil aviation accidents and incidents in the United States and international waters.

It includes the Make and Model of aircraft involved in incidents, location, weather conditions, and a reported number of fatal and non-fatal injuries. 

## Visualizations
**Overall Makes with Most Accidents Reported**
<img width="704" alt="Cessna, Piper, Beech, Boeing, and Air Tractor are listed. Cessna has the most accidents, and Air Tractor the Least." src="https://github.com/user-attachments/assets/947e339e-baf4-4fbc-849c-d4b64d3676d2">

**Commercial Flights with Most Accidents Reported**
<img width="704" alt="Cessna, Piper, Beech, Air Tractor and Raytheon are listed. Cessna has the most accidents, and Raytheon the Least." src="https://github.com/user-attachments/assets/739c1d40-063e-414e-aa02-f65804f9b311">

**Private Flights with Most Accidents Reported**
<img width="704" alt="Cessna, Piper, Beech, Mooney and Cirrus are listed. Cessna has the most accidents, and Raytheon the Least." src="https://github.com/user-attachments/assets/6f7d7b75-59c1-40e7-8de3-3b1e57ffb427">

## Conclusion
Our top three reccomendations were: 
* Boeing 757251 (**0% fatality rate** and a **1.3% injury rate**)
* Cessna 152 (**9.6% fatality rate** and a **15.4% injury rate**)
* Cessna 172-N (**11.3% fatality rate** and a **19.7% injury rate**)    

## Next Steps 
Further analysis could yield additional insights to further improve our aircraft recomendations. 

* **Acquire more robust aircraft flight data.** Quantifiying risk for aircraft makes/models could be more accurate if we incorporated data outside of only aircraft incidents. 

* **Financial Analysis.** Aircraft models, even variants of the same model, have very different operating costs. A financial analysis on aircrafts could identify the models with the lowest operating costs for our client. 
