# Modify the base shp file and update web map
To improve visiual of the map, calculate overall education level based on each education level's weight

## Set weight for each education level
1 - No certificate, diploma or degree
2 - High school diploma or equivalent
3 - Post secondary certificate, diploma or dgree include CEGEP or college level
4 - University certificate or diploma include Bachelor's Degree
5 - University certificate, diploma or dgree above bachelor level

## Create new field for education level
1. Open Webbed project on ArcGIS pro
2. Open attribute table
3. Add new field
4. Name as 'Education Level'
5. Save the change

## Calculate the value
1. Left click on 'Education Level' field
2. Seclect Calculate field
3. Put fuction ((Each education level)*Weights) Total population
4. Set symbology as unclassed colors

