## Analysis and Prediction of Disaster Frequency

## What exactly does this project do?

The system will provide real-time information on essential variables for agriculture, such as soil moisture, temperature, solar radiation and weather forecasts, helping farmers make more informed decisions and optimize their resources.

## How does it work?
1. Disaster Analysis by Country: We create graphs showing the frequency of disasters by type and by country over the past few years using Python, pandas, seaborn, and matplotlib.
2. Prediction with SARIMA: We use the SARIMA model to make predictions about the frequency of disasters in the next five years for each type of disaster.
3. Validation with Linear Regression: We implement a linear regression model to validate the results and compare them with the real data.
   
## Tools and Technologies Used
- Programming languages: Python
- Libraries: pandas, seaborn, matplotlib, statsmodels (SARIMA), scikit-learn (linear regression)
- Data analysis, prediction and visualization: Line graphs to show trends in the frequency per year of disasters by country and type (Focused on Latin America).
  
## Conclusions
The global graph shows how disasters have evolved and this helps us to discuss some cases for climate change focused on agriculture.
It was observed how floods and storms are the biggest global problem for agriculture with a tendency to decrease and it is time to improve. With these results we can see the changes in specific phenomena such as El Niño.

![image](https://github.com/user-attachments/assets/c3cbbfe4-f4c4-47d1-96cb-44022c1bc463)


## Trend: 
With this information we can observe how often earthquakes occur and every time we have some atypical data it could help us determine a disaster in the near future.
![image](https://github.com/user-attachments/assets/0e3a5f7a-e9f3-4588-b83e-0147062844a9)

## Forecast:
Sarima was used in this part, which allowed us to see how floods are the type of disaster that has caused the most rainfall over time, not only in Colombia but in other Latin American countries, having a way of being able to generate some improvements for crops in this specific area.
Linear regression: By implementing this method, we validate that the applied models are efficient.
![image](https://github.com/user-attachments/assets/1be08282-d6cb-4322-aec6-30d6ff78ecc9)

Geocoded Disasters (GDIS) Dataset
We are utilizing the Geocoded Disasters (GDIS) dataset, available through NASA's EarthData Search. This dataset provides extensive global records of environmental disasters, including floods, droughts, earthquakes, tsunamis, storms, volcanic activity, and more.

## The dataset spans from 1960 to 2018 and includes key fields such as:

## Country
Year of the disaster
Geolocation (Latitude and Longitude)
Disaster name
With a global scope, the GDIS dataset offers valuable insights for understanding the geographical distribution and impact of environmental disasters over time, aiding in climate and disaster research efforts.


https://search.earthdata.nasa.gov/search/granules?p=C2022273992-SEDAC&pg[0][v]=f&q=geocoded%20disasters&tl=1727916943!3!!


## NCA-LDAS Noah Land Surface Model Dataset
This dataset is a collection of daily processed data from the Noah Land Surface Model (NCA-LDAS), with a spatial resolution of 0.125 degrees. It is designed to support climate and meteorological research by providing high-resolution data on land surface conditions. The dataset is available through NASA’s EarthData Search and covers the period from 1979 to 2016.

https://search.earthdata.nasa.gov/search/granules?p=C1454297282-GES_DISC&pg[0][v]=f&pg[0][gsk]=-start_date&q=NCA-LDAS%20Noah&tl=1727916943!3!!

