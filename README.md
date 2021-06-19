# Time-Series-Prophet---Avocado-Prices-Prediction

- You must install fbprophet package as follows: 
     pip install fbprophet
     
- If you encounter an error, try: 
    conda install -c conda-forge fbprophet

- Prophet is open source software released by Facebook’s Core Data Science team.

- Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. 

- Prophet works best with time series that have strong seasonal effects and several seasons of historical data. 

- For more information, please check this out: https://research.fb.com/prophet-forecasting-at-scale/
https://facebook.github.io/prophet/docs/quick_start.html#python-api

### PREDICTING AVOCADO PRICES USING FACEBOOK PROPHET 

- Data represents weekly 2018 retail scan data for National retail volume (units) and price. 
- Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados. 
- The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags. 
- The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

Some relevant columns in the dataset:

- Date - The date of the observation
- AveragePrice - the average price of a single avocado
- type - conventional or organic
- year - the year
- Region - the city or region of the observation
- Total Volume - Total number of avocados sold
- 4046 - Total number of avocados with PLU 4046 sold
- 4225 - Total number of avocados with PLU 4225 sold
- 4770 - Total number of avocados with PLU 4770 sold

![image.png](https://www.flickr.com/photos/30478819@N08/33063122713)

### Visualized figures from code
##### Click on the image or open in new tab

- Bar Chart


![image](https://user-images.githubusercontent.com/82017895/122643521-da3b8780-d12d-11eb-980c-6162c047b1ce.png)

- Forcasing Image


![image](https://user-images.githubusercontent.com/82017895/122643542-f93a1980-d12d-11eb-9a2f-016dfc03f4ea.png)

![image](https://user-images.githubusercontent.com/82017895/122643583-2e466c00-d12e-11eb-9751-74765163c14a.png)


![image](https://user-images.githubusercontent.com/82017895/122643606-4ae2a400-d12e-11eb-832d-1186b87c43f9.png)

![image](https://user-images.githubusercontent.com/82017895/122643614-559d3900-d12e-11eb-8fbf-77074623f740.png)



