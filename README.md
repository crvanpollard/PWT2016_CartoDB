[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cartodb.png)](https://cartodb.com) 
## Intro to CartoDB workshop - PTW 2016 Map It Out (May 4, 2016)

Christopher Pollard, Manager, Geospatial Application Development @DVRPC

cpollard@dvrpc.org, [@CRVanPollard ](https://twitter.com/CRVanPollard)

### Today's goal - make this map
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/todaysmap.png)](https://cpollard.cartodb.com/viz/399ea10e-0f0e-11e6-a48d-0ecd1babdde5/public_map)

### How are we going to get there...
- Overview of CartoDB
- Getting started 
- Importing data into CartoDB
- Visualizing data in CartoDB (style wizard, infowindows, filters, cartocss)
- Sharing your visualization
- CartoDB Deep Insights (coming summer 2016)

## Overview of CartoDB
#### CartoDB Editor - https://cartodb.com/editor/
Easy to use web map editor helping people visualize and analyze geospatial data
- Connect, collect, and manage location data
- Analyze and understand where the impact or trends are occurring
- Discover insights, patterns, and visually share that information
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cartodbeditor.png)](https://cartodb.com/editor/)

#### CartoDB Platform - https://cartodb.com/platform/
A set of high performance APIs and tools to deliver geospatial applications with big data and extensible location analytic capabilities. CartoDB Editor is actually an application built on top of the CartoDB Platform.
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cartodbplatform.png)](https://cartodb.com/platform/)
#### What are people doing with it
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/iceland.png)](http://iceland.cartodb.com/tables/iceland/embed_map?title=true&description=true&search=false&shareable=false&cartodb_logo=true&sql=)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/sunrise.gif)](http://cartodb.s3.amazonaws.com/static_vizz/sunrise.html?title=true&description=true&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=false&scrollwheel=true&sublayer_options=1%7C1&sql=&zoom=2&center_lat=22.917922936146045&center_lon=51.328125#)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/streets.png)](http://illustreets.co.uk/explore-england/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/lasmog.png)](http://graphics.latimes.com/responsivemap-pollution-burdens/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/nycairbnb.png)](http://blog.cartodb.com/airbnb-impact/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/marktwain.png)](http://andrewxhill.com/maps/writers/twain/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cyclephilly.png)](http://www.dvrpc.org/webmaps/cyclephilly/)

## Getting Started

### Set up an account
If you don't have an account, go sign up: [https://cartodb.com/signup](https://cartodb.com/signup)  

### CartoDB Dashboard
This is where you can view and manage your maps and datasets
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/dashboard.png)](https://cpollard.cartodb.com/me)

## Importing data into CartoDB
### Supported geospatial data formats
http://docs.cartodb.com/cartodb-platform/import-api/importing-geospatial-data/#supported-geospatial-data-formats
- Shapefile
- KML/KMZ
- GeoJson
- CSV
- Spreadsheets (Excel or OpenDocument)
- GPX
- OSM

### Connecting data to CartoDB
There are different ways to import data into CartoDB. It can be files you have stored locally or datasets that you can connect to through Dropbox, Google Drive, Box, Twitter, ArcGIS Server, MailChimp, and SalesForce.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/connect.png)

### Datasets
Today, we are going to use several local datasets that focus on Bicycle planning.
I have already downloaded and placed them in my ([GitHub repo](https://github.com/crvanpollard/PWT2016_CartoDB/tree/master/data)) for our use today. Copy the following links below and paste them into your CartoDB importer

- Philadelphia Bike Network ([Open Data Philly](https://www.opendataphilly.org/dataset/bike-network))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/phl_bike_network.zip`

- DVRPC Bicycle Counts ([DVRPC GIS Portal](http://dvrpc.dvrpcgis.opendata.arcgis.com/datasets/f8cf3245754c4b79a89a04a5d278a450_0))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/dvrpc_bicycle_counts.csv`

- Census Tract Boundaries 2010 ([Census Geography](https://www.census.gov/geo/maps-data/data/tiger-line.html))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/censustracts2010.zip`

- Census 2009 - 2013 ACS Demographic Profiles ([DVRPC GIS Portal](http://dvrpc.dvrpcgis.opendata.arcgis.com/datasets/beb54980293b4c0fa5312f0eb8ffbb1f_0))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/asc2013_tract_data.csv`

### Data View
This is where you can view, sort, modfiy, add, and merge datasets together. Very similar to excel and other spreadsheet interfaces. 
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/dataview.png)
If you don't have a Geometry field or Lat/Long in your dataset you can use CartoDB's Georeferencing tool to be able to map your data by address, city name, postal code, admin. region, or IP address.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/datageo.png)
You can also merge datasets that have a common field or attribute in common.
We will do this with our Census Tract shapefile and ACS 2009-2013 Demographic Profile data.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/datamerge.png)

## Visualizing data in CartoDB (style wizard, infowindows, filters, cartocss)

## Sharing your visualization

## CartoDB Deep Insights (coming summer 2016)
Predictive analytics and on-the-fly visualiztion that will drastically improve CartoDB workflows and analysis.
Key take aways: 
- An actionable dashboard with <b><u>widgets</u></b> (charts and forms)
- <b><u>High Performace Analytics (HPA)</u></b> to not only view but now analysis <b>LARGE</b> amounts of data, FAST and quick
- Data Augmentation (DA) builds a relationship between 2 datasets and everything that surrounds that data.
DA is series of Aagorithms that geocode the data and adds valuable demographic data that’s open data (population, income, employment, etc..)

[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/di1.png)](https://cartodb.com/deep-insights/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/di2.png)](https://cartodb.com/deep-insights/)

## CartoDB Resources
#### CartCSS Reference Sheet - http://ebrelsford.github.io/talks/2014/Methods3/week7/materials/cartocss-reference.pdf
This handy CartCSS Reference Sheet is a quick guide for beginners to CartoCSS

#### CartoDB Academy - http://academy.cartodb.com
The CartoDB Academy is great for recapping the basics, starting to use their APIs, and growing your design capabilities.
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapacademy.png)](http://academy.cartodb.com)

#### Odyssey - http://cartodb.github.io/odyssey.js/
A simple way for journalists, designers, bloggers, and others to publish stories that combine narratives with map interactions. Always creators to weave interactive stories with images, maps, and compeling narritives.
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/odyssey.png)](http://cartodb.github.io/odyssey.js/)

#### Preparing CSV files for use in CartoDB - https://vimeo.com/channels/cartodb/100105203
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/csv.png)](https://vimeo.com/channels/cartodb/100105203)

#### Using Column Join to Merge Tables - https://vimeo.com/channels/cartodb/100105201
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/merge.png)](https://vimeo.com/channels/cartodb/100105201)

#### Bootstrap Starter Kit - https://github.com/chriswhong/cartodb-bootstrap-template
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/starterkit.png)](https://github.com/chriswhong/cartodb-bootstrap-template)


