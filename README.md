# EDA-on-EV-Canadian-Market
Our second Data Analytics group project in which we are analyzing the EV Canadian Market behavior from 2012 to 2026

Exploratory Data Analysis (EDA) for EV Energy Efficiency

Group Members:
Ioanna Birmpili,
Areti Krontiri,
Antonis Dagkalidis.

Folder 'Data':
Contains the .csv file used to retrieve the data.

Folder 'Dashboard':
Contains the .pbix file used to create the interactive dashboard.

Data Source:
https://www.kaggle.com/datasets/ahmeduzaki/ev-energy-efficiency-dataset/



The present analysis examines the evolution of the electric vehicle (EV) market in Canada from 2012 to 2026. 
As observed, the market is dominated by a small number of key manufacturers, with Tesla holding 15.37%, 
followed by Rivian (13.37%) and BMW (9.77%), while all remaining brands maintain a market share of less than 5.5%.

The geographical analysis indicates that the majority of EVs circulating in Canada originate from the United States and Germany. 
This suggests a clear preference among Canadian consumers for American and European manufacturers compared to the Asian market.

![alt-text](https://github.com/adagk/EDA-on-EV-Canadian-Market/blob/main/screenshots/Market_Overview.jpg)


Subsequently, we compare motor power with energy efficiency across brands, models, and vehicle types, focusing on the Top 10 of each 
category.

At the brand level, we observe that Lucid and Tesla exhibit the strongest balance between power and efficiency, with motor power 
ranging approximately between 410–563 kW and efficiency values from 5.11 to 5.88.

When analyzing individual models, we find that in the Top 10 rankings, the first four models originate exclusively from Lucid, 
which manages to maintain high efficiency levels even in high-power vehicles.

Finally, at the vehicle type level, we observe that as vehicle size decreases, horsepower also declines, 
while energy efficiency shows an increasing trend. The negative correlation between motor power and efficiency is further confirmed 
by the scatter plot, where increases in power are accompanied by decreases in efficiency.

![alt-text](https://github.com/adagk/EDA-on-EV-Canadian-Market/blob/main/screenshots/Motor_Efficiency.jpg)

Chronologically, from 2012 to 2016, a gradual increase in the presence of EVs in the Canadian market can be observed, 
with a peak in 2025. Although we are only in the first weeks of 2026, sales already show a tendency to approach or even exceed 
the levels of the previous year.

At the same time, similarly to the motor power vs. efficiency analysis, EVs from recent years are larger in size compared 
to earlier models (e.g., 2012), indicating a shift in consumer preferences. These vehicles feature higher power output but 
exhibit lower energy efficiency.

![alt-text](https://github.com/adagk/EDA-on-EV-Canadian-Market/blob/main/screenshots/Yearly_Evolution.jpg)

Of particular importance is the recharge time, which shows an upward trend over the years, 
following a pattern similar to the increase in horsepower.

In the scatter plot, a wide dispersion in charging times is observed; however, around 13 hours 
there is a high concentration of vehicles with varying power levels. This suggests that charging time is 
not determined solely by motor power.

![alt-text](https://github.com/adagk/EDA-on-EV-Canadian-Market/blob/main/screenshots/Recharge.jpg)

Finally, an additional reporting sheet is provided, in which the entire dataset is available, 
enabling export and further analysis by the user.

![alt-text](https://github.com/adagk/EDA-on-EV-Canadian-Market/blob/main/screenshots/Data_Report.jpg)