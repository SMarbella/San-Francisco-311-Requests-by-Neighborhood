# San-Francisco-311-Requests-by-Neighborhood
I used Google Data Studio (renamed to Google Looker Studio) to create an interactive map that shows the number of different types of San Francisco 311 service requests around the world, such as street and sidewalk cleaning, graffiti, and encampments. For example, clicking any location on the map gives the number and types of reported requests in the area.
![Image](https://github.com/SMarbella/San-Francisco-311-Requests-by-Neighborhood/blob/main/Images/GIS%20Mapping.png)

# Geographic Information System (GIS) Interactive Map
![Image](https://raw.githubusercontent.com/SMarbella/San-Francisco-311-Requests-by-Neighborhood/main/Gifs/GIS%20Interactive%20Map.gif)
This interactive map shows the different types of crimes from around the world. The cases from the San Francisco 311 dataset generate multiple circles of different sizes on the map.

Larger circles mean that there are more cases in that area. Smaller circles mean that there are fewer cases. Each circle comes from the record count found in the dataset.

# Filtration System (Case Status Tracker)
![Image](https://raw.githubusercontent.com/SMarbella/San-Francisco-311-Requests-by-Neighborhood/main/Gifs/Case%20Filtration%20System.gif)
The squares represent the proportion of cases under different criteria. The size of the squares represents the number of data under that criteria. The different sizes of the squares show that these San Francisco 311 requests fit under this criterion. Smaller squares have fewer cases with that certain criterion. It makes those criteria rare or unique cases.

For example, the largest square is the Resolved Cases. This means that the Google Looker Studio tool sorted all cases with the Resolved Cases into that square.

# Filtration System By Neighborhood
![Image](https://raw.githubusercontent.com/SMarbella/San-Francisco-311-Requests-by-Neighborhood/main/Gifs/Case%20Filtration%20System%202.gif)
The San Francisco 311 dataset includes neighborhood location data. This filtration system filters the data using neighborhood data. Anything with a checked box updates the map and case status tracker.
