# Air Pollution in the US. 
## Overview of the project.
- Created a study to predict air pollution trends in different cities in the US. Air pollution refers to the release of pollutants in the air that are harmful to humans and the environment. The pollutants studied were Nitrogen Dioxide(NO2), Ozone(O3), Sulfur Dioxide(SO2), and Carbon Monoxide(CO). According to the National Resources Defence Council(NRDC), four out of ten US residents live in counties with unhealthy levels of pollution. The Air Quality Index is used for to predict pollutant levels in the air by calculating in unit; microgram/cubic meter(ug/m3) and parts per million(ppm). 

## Purpose.
- The data we acquired was in form of a csv file that contained different cities AQI levels everyday for a whole year. The dataset was obtained from Kaggle website. The most harmful pollutant is CO therefore we focused on this pollutant to evaluate pollutions levels. Using this data, we were able to display the trend over time and ultimately predict upcoming pollution trends. We displayed the cities with the highest and lowest levels. 

## Project.
- The machine learning model was created using Jupyter Notebook. We imported all the necessary dependencies,

<img width="1009" alt="Project_Dependencies" src="https://user-images.githubusercontent.com/25447945/141702489-f92fee95-df97-4a90-b5e9-cfba5246585a.png">

  and then used sqlalchemy to connect our database with the machine learning model.
  
 <img width="1018" alt="sqlalchemy" src="https://user-images.githubusercontent.com/25447945/141702659-af22c579-5b86-4819-b478-40c89e23a7e8.png">
 
  and proceeded to run train split test on our x and y valuables. 
  
  <img width="1029" alt="Splitandfeatures" src="https://user-images.githubusercontent.com/25447945/141702697-c90e64d6-05ff-4e20-a699-2ea2fb9e4a35.png">
  
- Created a database using Amazon Web Services RDS and linked it to pgAdmin to edit the data. Using PostGresSQL, we were able to upload the csv file, extracted data, and           transformed it into a data frames. 
- Using Tableau to create dashboard to portray our visualization about the pollution in US and then discuss about most and least polluted city in US. 


## Summary.







## Resources.
- CSV, Tableau, Jupyter Notebook, pgAdmin, AWS RDS.
- NRDC.org (National Resources Defence Council)

