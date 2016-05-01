![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cartodb.png)[https://cartodb.com](https://cartodb.com)

#Intro to CartoDB workshop - PTW 2016 Map It Out (May 4, 2016)

Christopher Pollard

cpollard@dvrpc.org, [@CRVanPollard ](https://twitter.com/CRVanPollard)

## Today's goal - make this map
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/todaysmap.png)

## CartoDB workshop outline
- Overview of CartoDB
- Getting Started
- Importing data into CartoDB
- Visualizing data in CartoDB (style wizard, infowindows, filters, cartocss)
- Sharing your visualization
- CartoDB Deep Insights (coming summer 2016)

## Overview of CartoDB
#### What are people doing with it
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/sunrise.gif)](http://cartodb.s3.amazonaws.com/static_vizz/sunrise.html?title=true&description=true&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=false&scrollwheel=true&sublayer_options=1%7C1&sql=&zoom=2&center_lat=22.917922936146045&center_lon=51.328125#)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/streets.png)](http://illustreets.co.uk/explore-england/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/nycairbnb.png)](http://blog.cartodb.com/airbnb-impact/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/marktwain.png)](http://andrewxhill.com/maps/writers/twain/)
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/cyclephilly.png)](http://www.dvrpc.org/webmaps/cyclephilly/)
## Getting Started

### Set up an account
If you don't have an account, go sign up: [https://cartodb.com/signup](https://cartodb.com/signup)  

### Datasets
Today we are going to use several local datasets that focus on Bicycle data.
I have already downloaded and placed them in my ([GitHub repo](https://github.com/crvanpollard/PWT2016_CartoDB/tree/master/data)) for our use today. Copy the following links below and paste them into your CartoDB importer

- Philadelphia Bike Network ([Open Data Philly](https://www.opendataphilly.org/dataset/bike-network))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/phl_bike_network.zip`

- DVRPC Bicycle Counts ([DVRPC GIS Portal](http://dvrpc.dvrpcgis.opendata.arcgis.com/datasets/f8cf3245754c4b79a89a04a5d278a450_0))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/dvrpc_bicycle_counts.csv`

- Census Tract Boundaries 2010 ([Census Geography](https://www.census.gov/geo/maps-data/data/tiger-line.html))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/censustracts2010.zip`

- Census 2009 - 2013 ACS Demographic Profiles ([DVRPC GIS Portal](http://dvrpc.dvrpcgis.opendata.arcgis.com/datasets/beb54980293b4c0fa5312f0eb8ffbb1f_0))
`https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/data/asc2013_tract_data.csv`

## CartoDB Resources
This handy CartCSS Reference Sheet is a quick guide for beginners to CartoCSS
http://ebrelsford.github.io/talks/2014/Methods3/week7/materials/cartocss-reference.pdf

#### Preparing CSV files for use in CartoDB
https://vimeo.com/channels/cartodb/100105203
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/csv.png)](https://vimeo.com/channels/cartodb/100105203)

#### Using Column Join to Merge Tables
https://vimeo.com/channels/cartodb/100105201
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/merge.png)](https://vimeo.com/channels/cartodb/100105201)

#### CartoDB Academy
The CartoDB Academy is great for recapping the basics, starting to use our APIs, and growing your design capabilities
http://academy.cartodb.com
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapacademy.png)](http://academy.cartodb.com)

#### Odyssey
A simple way for journalists, designers, bloggers, and others to publish stories that combine narratives with map interactions. Always creators to weave interactive stories with images, maps, and compeling narritives.
http://cartodb.github.io/odyssey.js/
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/odyssey.png)](http://cartodb.github.io/odyssey.js/)

#### Bootstrap Starter Kit
https://github.com/chriswhong/cartodb-bootstrap-template
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/starterkit.png)](https://github.com/chriswhong/cartodb-bootstrap-template)
