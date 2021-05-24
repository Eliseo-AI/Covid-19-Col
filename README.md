Table of Content
================
* [Covid 19 Colombia](#Covid-19-Col)
  * [Description](#description)
  * [Process](#process)
  * [Files](#files)
  * [Results](#results)
  * [Installation guide](#installation-guide)
  * [Credits](#credits)
  * [Licensing](#licensing)
  
# Covid-19-Col
## Description

To carry out the analysis process, the data set for March 7, 2021 was started, in addition to a file of the 2018 census in Colombia and the latitude and longitude coordinates of all the municipalities of Colombia.
The first step was to explore the data set of covid-19 March 7, it is identified that the file has a significant number of rows and columns, so the quality of the data must be verified.

In a second step, the file was updated, moving to March 24 as the starting point, 2021, they include data such as: age, gender, department, municipality, patient's status, date of diagnosis, date of symptoms , recovery date, and other information per patient, there is no name or identification number of the patients.

## Process


## Files
  *Covid-19 (7th and 24th)
https://www.ins.gov.co/Noticias/Paginas/Coronavirus.aspx

  *Census 2018 (Colombia)
https://www.dane.gov.co

  *Latitude and Longitude (Municipalities in Colombia)
https://geoportal.dane.gov.co/geovisores/territorio/consulta-divipola-division-politico-administrativa-de-colombia/

## Results
* Dataset from March 6,2020 to march 7, 2021.
* Dataset from March 6, 2020 to march 24, 2021.
* Shape (2276656, 23), Shape (2347224, 23)

![](Images/Deceased%20groups.png)
- Most of the infected people are between 25 and 54 years old, these people are economically active and must be studying or working, the difference in the number of infected people by gender is small, but there are more men identified than women.
![](Images/Distribution%20Covid-19.png)
- Most of the people who died in the analyzed period are people over 55 years of age and in all age groups it affects men in a greater number.
![](Images/Ethnic%20groups.png)
- There are five identified ethnic groups, but there is no significant difference that the disease has a difference in the age group of people who are infected.
![](Images/Location%202.png)

![](Images/Distribution%20by%20departments.png)
- Bogotá, the capital has almost a quarter of the deceased, the next three departments have added a little more than another quarter of the deceased.
![](Images/Evolution.png)
- During the period of the pandemic analyzed, two peaks of cases are identified, the second peak has a greater number of deaths.
![](Images/top%20days.png)
- The ten days with the highest number of deaths are located in the second peak of deaths, the exact dates can be identified.
![](Images/time%20of%20diagnosis.png)
- It is identified that the periods of time to identify a person with the disease and their death was in most cases at least one month before their death, but in many cases it is only one week, in an important group it is postmortem.
![](Images/test%20of%20PCR.png)
- At least 100 patients who were recognized as recovered by PCR test died within a few days and have not been recognized as deceased by covid.

## Installation guide

If you use conda, you can install: 

   * conda install pandas
   * conda install seaborn
   * conda install numpy

If you use pip, you can install: 

   * pip install pandas
   * pip install seaborn
   * pip install numpy
    
## Credits
The analysis of the dataset was carried out by Eliseo B.
the file is in jupiternotebook format "covid_col_24.pynb"

The information of it is available at:

 *Covid-19 (7th and 24th)
https://www.ins.gov.co/Noticias/Paginas/Coronavirus.aspx

  *Census 2018 (Colombia)
https://www.dane.gov.co

  *Latitude and Longitude (Municipalities in Colombia)
https://geoportal.dane.gov.co/geovisores/territorio/consulta-divipola-division-politico-administrativa-de-colombia/

## Licensing
 Apache License Version 2.0, Eliseo Baquero 2021
