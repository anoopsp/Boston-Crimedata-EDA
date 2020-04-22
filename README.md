# Boston City Crime EDA

Crime incident reports are provided by Boston Police Department (BPD) to document the initial details surrounding an incident to which BPD officers respond. This is a dataset containing records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred.

## Project Motivation

* _What are the common types of crimes which occur?_
* _Which are the most affected districts?_
* _Does crime vary based on weekdays and month?._

## Installation

We will be using python programming language in the Jupyter Notebook. The jupyter notebook uses the standard Anaconda Distribution with the below mentioned packages installed. For Choropleth maps, we need to install folium python package, as its not part of standard distribution. 

```sh
$ import pandas as pd
$ import seaborn as sns
$ import matplotlib.pyplot as plt
$ pip install folium
$ import folium
$ from folium.plugins import HeatMap
```

## Datasets

The dataset folder consists of _'Data.csv'_ and _'Boston_Neighborhoods.geojson'_

The datasets required for EDA are downloaded from https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system.


## Interaction with the project

If the user has jupyter notebook and necessary anaconda distribution. We can easily run the jupyter notebook to visualise the data. User needs to download the data files provided in the dataset folder.

The notebook _Boston Crime EDA.ipynb_ can be easily executed once the necessary packages are installed.


##  Acknowledgements

* The picture is referenced from "https://assets.penguinrandomhouse.com/wp-content/uploads/2015/12/02152125/PRH-True-Crime-List-1400x380.jpg"
* The GeoJson file is downloaded from https://www.kaggle.com/yingzhou474/boston-neighborhoods-geojson

## License

The license information is available in 'LICENSE.TXT'
