### Lab 4 Geog 458, Live Web Map Link: https://dhritiy.github.io/Lab4_458/

##### For my map, I decided to focus on the general Seattle, Washington area. I used a minimum zoom level of 10 and a maximum zoom level of 14 while creating all of my tiles.
### Tile 1: Modified Basemap
![Tile 1](https://github.com/dhritiy/Lab4_458/blob/main/img/Tile1.PNG)

##### Caption: In order to create this basemap, I started with the Light Monochromatic themed basemap on Mapbox. Then from here, I wanted to start by altering the colors so that I could make the basemap have a bit more contrast. I changed the water to dark blue and also changed the greenspace to pale green. For all of these base colors, I chose dull colors so that data/text on this map would be more easily readable. Then I also changed all the font on my map to variations of Arial Unicode because I thought this would make the map easier to read. I also edited the labels to match the color scheme of my map. Greenspaces have dark green labels and icons, and all other blue areas (land, roads, waters) have a dark blue labels and icons.

### Tile 2: Thematic Map (Seattle Restaurant Satisfactory Rating)
![Tile 2](https://github.com/dhritiy/Lab4_458/blob/main/img/Tile2.PNG)

##### Caption: For Tile 2, I sourced my data from King County's geospatial database. I was looking specifically for restaurant data and found that King County had data on the locations of restaurants and also on whether they had a generic "Satisfactory" or "Unsatisfactory" rating. From here, I downloaded the shapefile and loaded into QGis. I filtered the dataset to only include restaurants in Seattle. Then I symbolized a satisfactory restaurant with a green point and an unsatisfactory restaurant with a red point. 

Data Source: https://gis-kingcounty.opendata.arcgis.com/datasets/restaurant-inspections-restaurant-inspections-point/data?orderBy=SCORE_INSPECTION&orderByAsc=false&selectedAttribute=RESULT_INSPECTION&where=CITY%20%3D%20%27Seattle%27

### Tile 3: Basemap with Data
![Tile 3](https://github.com/dhritiy/Lab4_458/blob/main/img/Tile3.PNG)

##### Caption: I created this tile by layer both of the layers from Tile 1 and Tile 2 together. On QGis, I selected and loaded both my modified basemap and the Seattle restaurant data. Then I outputted both together to create this layer.

### Tile 4: Seattle Seahawks Themed Basemap
![Tile 4](https://github.com/dhritiy/Lab4_458/blob/main/img/Tile4.PNG)

##### Caption: For my customized theme, I chose to make a Seattle Seahaws themed basemap because I am a big football fan. First, I looked up the hex codes for the Seahawks three colors, blue, green, and silver. Then I chose to make my base, land, and water colors blue. I chose to use the green for the roads since it is a very bright color and I thought it would be a nice contrast with the blue. Then I made all of the city labels, points of interest labels, and icons all the silver color. Some icons are also the blue and have a silver outline. 
