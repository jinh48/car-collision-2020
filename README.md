# Car Collision in Seattle (2020)

### This is an assignment for UW GEOG 458 - Lab 4: Map Design and Tile Generation

**This Repo contains:**
* Main html file for map display
* Image folder for map tiles result
* Assets folder for tile photo

[Link](https://jinh48.github.io/car-collision-2020/index.html) for the interactive map page. 
____________________________________________________________________________________________________________________________________________________________________

## Introduction and Credits:

The map simply displays the geospatial location of the car collision in Seattle, Washington during the 2020 timestamp. Below will shows all the screenshots of the tile layers with brief descriptions. Please note that the tiles are only covering the Seattle area as the location is the main focus. I wasn't able to increase the tile level (in other words, to allow to zoom in more closely) due to the massive amount of time for the machine to generate over 30,000 tiles. The highest level I tried was at 17th and noticed that the labeling and dots were still shrinking as I zoomed in. I figure it wasn't worth the view and the huge amount of time of waiting.   

I would like to thanks UW Professor Bo Zhao and his team for creating this lab for educational purposes. I also would like to credit the Github user [ppete2](https://github.com/ppete2/Leaflet.PolylineMeasure) for using the Leaflet plug-in. 

## Tile 1 - Modified Basemap

![tile 1](img/tile1.png)

* Examined georaphic area: Within Seattle, WA
* Zoom levels: Min: 11, Max: 15
* Brief description: This tile will mainly focus on the road networks, thus, getting different colors of roads and make them brighter to see easily against the black background. Each color representing the different types of roads (highways, major roads, etc.) 

## Tile 2 - Data for Car Collision Location

![tile 2](img/tile2.png)

* Examined georaphic area: Within Seattle, WA
* Zoom levels: Min: 11, Max: 15
* Brief description: This tile will mainly focus on the geodata, which is the location that occurred car collision. I styled the icon to make it more appealing and relevant to the theme. 

## Tile 3 - Basemap with Data

![tile 3](img/tile3.png)

* Examined georaphic area: Within Seattle, WA
* Zoom levels: Min: 11, Max: 15
* Brief description: The tile contains the combination of Tile 1 and Tile 2, utilizing the full effect of seeing the location of car collisions on easy-to-read roads.

## Tile 4 - Nature/Landscape/3D Building Theme map

![tile 4](img/tile4.png)
* Examined georaphic area: Within Seattle, WA
* Zoom levels: Min: 11, Max: 15
* Brief description: The tile doesn't relate to other tiles, this is just for fun. It is mainly focused on the color of the land, land use, and the shape of the buildings rather than the colors of the road network. Unfortunately, I wasn't able to pass the 18th level due to massive time for generating a lot of tiles.  

