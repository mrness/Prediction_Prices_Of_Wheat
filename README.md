# NU FinTech Project 1 Group 3
In this project we posed as consultants to Kraft-Heinz Corportaion. We noticed that the price of wheat is increasing. Wheat is a critical input for Kraft-Heinz products and the increase in prices is cutting into the bottom line. With this investigation we set out to better understand what factors may be correlated to the increase in wheat prices. Our working hypothesis is that rising oil prices are the most impactful factor, but it may also be related to carbon emissions, drought index, volatility of the US dollar, and the price of urea (nitrogen fertilizer) and copper as a critical farming inputs. Additionally, we wanted to map out the countries that are the largest importers and exporters of wheat products. 

## Libraries
In order to run our code these are libraries that need to be installed. 
- investpy
- html5lib
- pandas
- numpy 
- yfinance
- geopandas
- keplergl
- pathlib
- seaborn
- matplotlib.pyplot

## Data
All of the necessary dat to run our code can be found in the "Data" folder

## Code Modules
Our final combined code can be found in the "Notebooks" folder -> master-notebook.ipynb

We divided our project in to the following code modules 
- Price of wheat over time
- Kraft Heinz Stock Trends
- Correlation between wheat, carbon, and crude futures
- Correlation between wheat, copper, the dollar index, and drought
- Map visualizations of largest importers and exporters of wheat (Please note this code does not show the map visualization in a jupyter notebook, but the visualizations appear in colab)

## Graphs
Note : All graphs are in folder: Data

The diagram bellow shows the trend between all commodites and indexs we had in our analysis
we can see in plot 2014 period to mid 2015 the oil prices went down then automatically wheat prices went down in same period due to many factors:
1.Russia annexed crimea caused a disruption of Global wheal supply in 2014 to control the black Sea which is the port to export 
the wheat out of Ukraine which is the fifth largest wheat exporter.
![image](https://user-images.githubusercontent.com/69637182/184124010-e4169f90-8e1a-4a6a-84b0-5179ca08e3f0.png)

The secode diagram shows Urea(Fertilizer) is highly correlated with wheat price if Urea goes up the wheat goes up automatically 
![image](https://user-images.githubusercontent.com/69637182/184124980-03c76ff3-0522-4dd7-9366-817f430ad272.png)

Thirdly the wheat trends bellow shows significantly high trend in 2012/2013 because it was the best year of harvesting no drought no flood throughout season
after that in 2016/107 trend was pretty steep downwards for many reasons: Weaken of US dollars in this period, the trade war between US And China and at the end 
of 2022 the wheat trends jumped back up as it was in 2013 because the pandemic played major role of changing global wheat market directions.
![image](https://user-images.githubusercontent.com/69637182/184125457-082906de-da2f-46fe-a636-fdfc10db11f5.png)

The fourth plot is 21 window mean prices for 10 years period 
![image](https://user-images.githubusercontent.com/69637182/184161233-3d1e2d03-6840-4cf6-abf8-ef69bdb13925.png)

The fifth plot 21 window std and we can high volatilitity throught 10 years persiod 
![image](https://user-images.githubusercontent.com/69637182/184161575-ea5ab4a4-6196-411f-83ba-0223c1ab4798.png)

Lastly I overlayed 2 plots one with noise and the other without noise: the smoothest rolling mean
![image](https://user-images.githubusercontent.com/69637182/184162120-33aa630b-0c1e-409f-8711-fa6ffecd85ea.png)

# Conclusion 
The wheat market is projecting a CAGR of 4.5% of period 2022/2027 under a new restrictions because of pandemic when supply chain got distruped the wheat supply got reduced.









