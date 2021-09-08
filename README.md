
# Indian Railways WalkThrough

A casual walkthrough through datasets consisting information about trains and stations under different zones of Indian Railways.

## Acknowledgements

 - [Dataset](https://www.kaggle.com/sripaadsrinivasan/indian-railways-dataset)
 - [India ShapeFile for plotting](https://www.indianremotesensing.com/2017/01/Download-India-shapefile-with-kashmir.html)
 
  
## Introduction

Indian Railways is one of the largest railway networks operated by the Government of India. Railways was first introduced in India in 1853. Today, its operations cover 28 states and 8 union territories. It is also one of the busiest rail networks in the world, carrying about 18 million passengers daily.

The history of Indian Railways goes back to the year 1853 when the first train steamed off from Bombay to Thane, a distance of 34 km. 

About 12,000 trains go one place to another everyday. Railway is like a life line to the people of India. The route length of over 62,600 KM throughout the country. It operates in Broad Gauge, Meter Gauge, and Narrow Gauge operations in various geographical areas such as mountain terrains, long tunnels, on sea bridges and others.

With this notebook we have analyzed 3 different json files available via kaggle

- `stations.json` to know about the different stations present in this big network.
- `trains.json` have information about all the trains running currently.
- `schedules.json` to get the info about schedules about trains running.

With the <b>stations.json</b> we have a information about the railway stations present in India with this we will get info about how the stations are distributed and which is the northern , southern , eastern and western stations respectively.

With the <b>trains.json</b> we get info about different zones and which zone is handling how much trains also we get to know the train taking the most time to cover to the one taking the lowest time and plotted them in map of India using geopandas.

With the <b>schedules.json</b> we get info of different trains schedule and check which has highest number of stops and which is the busiest stations of all.

Basically this is just a fun walkthrough of the Indian Railways dataset.

## 🛠 Libraries worked upon

- Numpy
- Pandas
- Matplotlib
- Seaborn 
- GeoPandas
