<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Impact of Climate Change in Business 
## How will global warming impact business and companies?

*By:
Inês Garcia  
Sofia Sousa*

*Data Squad #21  
Lisbon  
September 2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
In this project we assume the position of employees of a data analysis team of a energy company in Portugal.
Our goal is to understand if and how climate events impact energy production and work productivity. 

The data used is from PORDATA, a database that aggregates data from several portuguese and european official sources. 

You can see all data preparation steps with all the explainations of data manipulation and filtering in the Project V Juptyter Notebook.

The folder 'data' has all the datasets used, the folder Work notebooks has the work notebooks (raw and unorganized worflow). 


<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
Overall we intended to understand how climate event impact business, in particular energy companies.

After the initial analysis of the data available other two hypothesis arose:
1. What is the impact of drought in energy production
2. Impact of heatwaves in Work Productivity
3. Impact of heatwaves in energy consumption
4. How do climate events impact energy companies' stock behaviour?

<a name="dataset"></a>

## Dataset
All the datasets were imported from PORDATA, a project that agregates several indicators from other sources, as well as EURONEXT Lisbon, for all the information regarding EDP stock information. 

[PORDATA](https://www.pordata.pt/Portugal)  
[EURONEXT Lisbon](https://live.euronext.com/pt/product/equities/PTEDP0AM0009-XLIS)


<a name="workflow"></a>

## Workflow

1. Research and data collection: We started by deciding on the subject and search for availabe data, collecting the most relevant. After this we questioned what did we wanted to know and what could be answered by the information availabe.
2. Data cleaning and database creation: After identifying the most relevant data we proceded to its cleaning and manipulation. The data was cleanned using pandas in Jupyter Notebook. For weather and enviornmental related data we decided to melt all the information, in order to mantain the maximum of detail possible. After that the dataframes were merged. In the merging process some of the data will be lost. This is due to the fact that some of the indicators only have information as from 1995, while other have it as from 1970, namely the weather related data. We assume that is acceptable to lose this information, since it will not have an impact on our conclusions. 
3. Insights and conclusions:
4. Data visualization and final presentation: Data visualization and presentation was done with Tableau. 


<a name="organization"></a>

## Organization
In this project we applied divided the work between the team members in order to deliver all the outputs requested, with the maximum quality possible. 

<a name="links"></a>

## Links
[Inês Garcia Repository](https://github.com/Inrx)    
[Sofia Sousa Repository](https://github.com/sofia-sousa)   
[Tableau Dashboard](https://github.com/Inrx/week-4-project/blob/642da30fd004cab10b15d6d6a6289680b015fc39/Public%20Presentation.pdf)  
[Trello](https://trello.com/b/dV3yxotJ/week-4-project) 
