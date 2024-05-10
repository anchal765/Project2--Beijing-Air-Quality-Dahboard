# Project2--Beijing-Air-Quality-Dahboard
##About Data:

This is the real world Beijing data of year 2004-2005 taken from Machine learning repository.

###Problem Statement:

The air quality in Beijing, China, has long been a matter of concern due to its significant impact on public health and environmental sustainability. Despite efforts to mitigate pollution, Beijing continues to face challenges in maintaining satisfactory air quality levels. To address this issue effectively, a comprehensive analysis of Beijing's air quality data is essential.

The primary problem revolves around understanding the dynamics of air pollution in Beijing, identifying key contributing factors, and devising strategies for improvement.This entails:

Data Collection and Preparation: Gathering comprehensive datasets encompassing various air quality parameters such as Benzene(Hourly Avg), NMHC, sulfur, nitrogen dioxide (NO2), carbon monoxide (CO), ozone (O3), and meteorological variables like temperature, humidity.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a (.xlsx) file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in Time column another wrong date is given which needs to be removed by splitting the column by 10 characters and then remove the Time.1 column. And then Merge the date and time column with the name Date and Time.
- Step 5 : The name of the column was given by formula so rename the column by the name of the gas like CO as carbon monoxide, NMHC as Non methanic hydro carbon ,C6H6 as benzene and more.
- Step 6 :In all the column there is a wrong values which are filled as -200 and this -200 must be replace by the average value of the column.

In the report view, under the view tab, theme was selected.

- Step 7 : Two Card Visuals were added to canvas to represent "Hottest day with time" and "Most humid day".
<img width="157" alt="Screenshot 2024-05-10 184008" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/eaffa3b4-6e8c-4c19-90e4-e4cb739dd9ff">
<img width="155" alt="Screenshot 2024-05-10 184029" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/cbcbff2e-d8a4-4852-9063-342535d010ea">

- Step 8 : To Represent "Average Temperature in Celsius ","Average Humidity", "Average of Ozone" a new visual was added using the three "Gauge" in the visualizations pane in report view.
<img width="136" alt="Screenshot 2024-05-10 183858" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/b9c6a4d5-dd4b-46aa-aa19-8d08354333bf">
<img width="137" alt="Screenshot 2024-05-10 183842" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/6e929e27-b0f8-4328-81f3-81a79de91447">
<img width="136" alt="Screenshot 2024-05-10 183917" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/4f386d29-c759-4fe6-8657-a36e30e2ac12">

- Step 9 : Use "Pie Chart" visual to represent the average of all the gases which are necessary to check the air quality.
<img width="296" alt="Screenshot 2024-05-10 183932" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/e597b463-56bb-4988-859a-83f8f943e02f">

- Step 10 : A Line chart is added to visualize the average of temperature and average of humidity by months.
- <img width="454" alt="Screenshot 2024-05-10 183952" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/60693e21-fc91-445b-a8a4-69d3a8d31185">
- Step 11 : A Slicer is also added to visualize all the data from date 10-03-2004 to 04-04-2005.
  <img width="137" alt="Screenshot 2024-05-10 183826" src="https://github.com/anchal765/Project2--Beijing-Air-Quality-Dahboard/assets/105012057/2902222b-2fa5-446b-993e-9555a734eda5">
