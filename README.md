# EMSI_Job Change UK _ Dashboard Project
This project visualises the **EMSI Job Change UK** dataset using Tableau.  
It highlights percentage job changes across regions and sub-industries, supported by interactive visuals and a UK geographic map.


## Project Contents
- `EMSI_JobChange_UK.xlsx` — Dataset used for the dashboard
- `Images/` — Contains screenshots of the visuals
- `README.md` — Project explanation


## Dashboard Screenshots
### % of Job Change UK Dashboard 
![Main Dashboard](Images/%25%20of%20Job%20Change%20UK%20Dashboard.jpg)

### Percentage Change by Sub_industry 
![Percentage Change by Sub-industry](Images/Percentage%20Change%20by%20Sub-industry.jpg)


### Map of % Change  
![Map of % Change](Images/Map%20of%20%25%20Change.jpg)

### Calculated Field  
![Calculated Field](Images/Percentage%20Change%20by%20Sub-industry.jpg)


## Interactive Dashboard (Tableau Public)
View the live dashboard here:
[Tableau Public Dashboard][Tableau Public Dashboard](https://public.tableau.com/views/TableauD1_17652250520960/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


## Project Overview
This project focuses on analysing labour-market shifts across the UK using the EMSI Job Change dataset.  
The dashboard presents:

- Percentage increase and decrease in job roles  
- Regional job change patterns  
- City/area-based differences visualised on a UK map  
- Sub-industry performance insights  

The goal is to provide a clear, visual understanding of how job demand is changing across the country.


## Tableau Calculated Fields

Here is an example of the calculation used to compute the percentage job change:
```text
SUM([Change] - [Change (2 digit)])
```

## Tools Used
Tableau Public - Dashboard creation and visualisation 
