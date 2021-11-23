# Air Pollution in the US. 
## Overview of the project.
- Created a study to predict air pollution trends in different cities in the US. Air pollution refers to the release of pollutants in the air that are harmful to humans and the environment. The pollutants studied were Nitrogen Dioxide(NO2), Ozone(O3), Sulfur Dioxide(SO2), and Carbon Monoxide(CO). According to the National Resources Defence Council(NRDC), four out of ten US residents live in counties with unhealthy levels of pollution. The Air Quality Index is used for to predict pollutant levels in the air by calculating in unit; microgram/cubic meter(ug/m3) and parts per million(ppm). 

## Purpose.
- The data we acquired was in form of a csv file that contained different cities AQI levels everyday for a whole year. The dataset was obtained from Kaggle website. The most harmful pollutant is CO therefore we focused on this pollutant to evaluate pollutions levels. Using this data, we were able to display the trend over time and ultimately predict upcoming pollution trends. We displayed the cities with the highest and lowest levels. 

## Project.
- The machine learning model was created using Jupyter Notebook. We imported all the necessary dependencies,

![dependdencies](https://user-images.githubusercontent.com/83738699/142091251-0b188841-469b-4a93-bc3d-845105d964e8.PNG)

 and then used sqlalchemy to connect our database with the machine learning model.
  
![Capture](https://user-images.githubusercontent.com/83738699/142089716-e81a983a-2caa-4bcb-a9b9-498fa6e0c778.PNG)
 
  Proceeded to run train split test on our x and y valuables. 
  
  <img width="1029" alt="Splitandfeatures" src="https://user-images.githubusercontent.com/25447945/141702697-c90e64d6-05ff-4e20-a699-2ea2fb9e4a35.png">
  
- Linear_Regression Model:
<img width="443" alt="Linear_Regression" src="https://user-images.githubusercontent.com/25447945/142797772-99c7b6ab-3a39-4c1f-b45e-ddf64113d01f.png"> 
- Created a database using Amazon Web Services RDS and linked it to pgAdmin to edit the data. Using PostGresSQL, we were able to upload the csv file, extract data, and           transform it into data frames. 
- Used Tableau to create dashboard to portray our visualization about the pollution in US and, then discuss the most and least polluted city in US. 

## Summary.







## Resources.
- CSV, Tableau, Jupyter Notebook, pgAdmin, AWS RDS.
- NRDC.org (National Resources Defence Council)
- [link to dashboard](https://public.tableau.com/app/profile/charity.thuku/viz/PollutionintheUS_/PollutionintheUS)
- [link to presentation](https://docs.google.com/presentation/d/1UGTwaaK8IIdT6UrpURS35Q7lxQieQtfCRig6affKTI8/edit?usp=sharing)

