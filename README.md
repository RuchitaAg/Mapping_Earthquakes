# Mapping_Earthquakes

## Objective:

This project shows visualisation created for Disaster Reporting Netwrok with the earthquakes data of past 7 days from all around the world on different types of maps to depict the earthquake data in relation to the tectonic plates’ location on the earth and create a third map to show major earthquakes with a magnitude greater than 4.5 on the map

**Technology used**: Mapbox API, GeoJSON data, JS, D3, Leaflet libraries

**Source**: US Geological Survey Website

## Outcomes:

The maps that are used in this project are street and satellite view and for the additonal layering a dark type mode is added. 

### Street View for all earthquakes:

![Mapping all earthquakes](https://user-images.githubusercontent.com/102870991/193432719-ba42e511-7640-4d81-84b5-35d85b3ae935.png)


### Satellite view for all earthquakes:

![image](https://user-images.githubusercontent.com/102870991/193432803-e5cb9e2b-566c-49b8-80de-c44eeab4113e.png)


## Deliverable 2: 
### Street View for major earthquakes:

In the data representation, two types of data is used. In one layer all the earthquakes data are represented. In other layer, the data is represented after applying a filter to filter out the major earthquakes, which gives the high magnitude earthquakes as shown below

![Mapping major earthquakes](https://user-images.githubusercontent.com/102870991/193432748-222e519c-cbca-4d42-b660-0a68d3b38e72.png)


## Deliverable 3
### Additional Map

We can choose different layers and view the data on these different maps using the program. For this purpose a layer of black mode is added:

![Mapping all earthquakes_dark mode](https://user-images.githubusercontent.com/102870991/193432769-c0d284c0-8f5d-4f97-9281-42f80920de36.png)


## How to run the program

To run the program, first we need to navigate to the main project directory, where the **static** folder and the **index.html** file present. Then need run the following command on command prompt terminal.

_python -m http.server_

Then copy following command and paste it on the browser as an url.

_localhost:8000_

Refer folder Mapping_Earthquake for the script.
Thank You
