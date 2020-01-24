# solar-energy-analysis
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Repisotory content](#setup)

## General info
This project is to study the impact of having a solar panel in the house as a feature, analysing the market time satistics, the value of the house. In order to do that we  have used inferentiel statistics tools, we selected a sample randomly from 'www.Mls.com/..' and we considered that as our main population. Then we flitered the houses that have solar panels and study them as a sample of our main population. 
By observing the dataframe and calculating the mean, the variance and standard deviation we eneded up with the first Hypotheis:
Hypothesis 1: Homes with solar panel systems have a higher average value than homes in general. We used z test to find out about statistical signficance about our H alternative.
Hypothesis 2: Existing homes with solar panel systems spend less time on the market than existing homes in general.
The second test is to compare the average market time, in days, of existing homes with solar panels to existing homes without. 
Hypothesis 3: New construction homes with solar panel systems spend less time on the market than new construction homes without.Hypothesis 4: Homes with solar panel systems have a final sale price closer to the original listing price when compared to homes in general.
We used python language to build many tools to clean the data and also use some inferentiel tools from its libraries. We put everything together in a repisotory on github.
 
	
## Technologies
Project is created with:
* python: 3.3
* version: 2.33
* libraries : numpy,matplotlib.pyplot,pandas, seaborn, random, pickle, statsmodels, scipy 

	
## Repisotory content:
Data_processing.ipynb is a file that has the whole code including build fonctions that was used to clean up the tables we got from the website.
Hypothesis_Testing.ipynb is a file that includes all testings for each hypothesis with some technical conclusions 

