## GIS for Arauca
This project was created to show the encironmental effects that oil companies had on the hydrological system called Lipa in Arauca, Colombia. The base is an OpenStreetMap and the additions come from participatory cartography and field work conducted in November 2024. 
You can find the map here: [gisarauca.github.io](gisarauca.github.io)

## Reproducing the Map
I created the map in QGIS 3.40 using the plugins
- QuickOSM
- ImportPhotos
- QGIS2Web
- LatLon-Tools

The dried-ought rivers were scouted using ESRI-Satelite images.

## Further ideas
- Integrating data from communal monitoring
During the communal monitoring a lot of quite unstructured data is generated. A lab takes samples of water and bio-matter and tests it for things such as pH, O2-concentration, heavy metal-concentration etc. A probe from the waters at PF2 looks like this: 
“Reporte hora 14:00 
pH: 8.17
Conductividad: 537
Temperatura: 33.3 
Oxígeno Disuelto: 5.29”
One could easily write a program which extracts the numbers and fills a spreadsheet with that creating a csv-file. This csv-file could be imported into QGIS and one could color parts of the rivers with high concentrations of certain toxins in other colors and therefor help the local population in deciding where it is safe to eat fish from the rivers and where it is best avoided.
