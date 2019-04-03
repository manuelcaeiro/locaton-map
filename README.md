# locaton-map
A Python/Folium creator of the geolocalisation map for the CSV representation of Nuclear Waste Sites on US Campuses

![](https://github.com/manuelcaeiro/locaton-map/blob/master/screenshots/map1r.jpg)

(With minor changes it will create a map from any other CSV file with latitude-longitude value pairs)

# About the map
The source data for the CSV file was obtained [here](https://github.com/plotly/datasets/blob/master/Nuclear%20Waste%20Sites%20on%20American%20Campuses.csv)

[Folium](https://github.com/python-visualization/folium) module has some great [features](https://python-visualization.github.io/folium/) (and is missing some needful others. Notice that in order to have a title on the map it was necessary to introduce an HTML element inside the Python code.)

# How to use
To make use of this program it is necessary a computer with Python 3 installed, the Folium module, an IDE or a code editor able to run Python, and an internet connection.

- Download the files ["nuclear\_waste\_on\_campuses.py"](https://github.com/manuelcaeiro/locaton-map/blob/master/nuclear_waste_on_campuses.py) and ["Nuclear\_Waste\_Sites\_on\_US_campuses.csv"](https://github.com/manuelcaeiro/locaton-map/blob/master/Nuclear_Waste_Sites_on_US_Campuses.csv) to the same directory (folder);
- Open and run the .py file. A file named "map\_nuclear\_on_campus.html" will be created in the same directory (folder);
- Connected to the internet open the just created HTML file on a browser and the map should load (it was tested with Firefox, Chrome and Opera;)
- Click on a mark to see the name of the corresponding site, zoom in to individualize agglomerates of marks, and further to check the names of the streets around a site.

![](https://github.com/manuelcaeiro/locaton-map/blob/master/screenshots/map2r.jpg)

# Licenses
Copyright [2019] [J. Manuel Caeiro D. P.]

The code in this repository is under the _MIT License_. You may obtain a copy of the _MIT License_ [here](https://opensource.org/licenses/MIT)

Plotly Sample Datasets are under _GPL-3 License_, as explained [here](https://github.com/plotly/datasets/blob/master/LICENSE).

# TO-DO
- Upon request (plus a generous donation): Build CSV files to geolocalise other interesting places and change the code to display them.
