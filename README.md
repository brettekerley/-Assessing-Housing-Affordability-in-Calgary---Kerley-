# Housing Affordability in Calgary

## Overview
This project analyzes housing affordability in Calgary, focusing on how proximity to transit, parks, and schools influences housing prices. Using spatial and statistical analysis techniques, this project provides insights into affordability trends and aims to inform urban planning for equitable housing solutions.

## Objectives
1. Analyze how proximity to transit, parks, and schools impacts housing prices in Calgary.
2. Create clear and reproducible geospatial visualizations to share publicly.
3. Promote open data sharing to support future urban planning initiatives.
4. Provide actionable insights for policymakers to address housing affordability challenges.

## Data Sources
- **City of Calgary Open Data Portal**: Housing prices, transit routes, and parks.
- **Statistics Canada 2021 Census**: Population demographics and income levels.
- **Calgary Real Estate Board (CREB)**: Housing market trends.

## Repository Structure
- `data/`: Contains datasets in CSV format.
- `maps/`: Generated geospatial map outputs.

## Maps
1. **Housing Prices and Transit Proximity**: Displays the relationship between housing prices and distance from transit stations.
2. **Parks and Housing Affordability**: Highlights the influence of park proximity on property values.
3. **Schools and Neighborhood Desirability**: Shows how access to schools affects housing affordability.

## License
This project is licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgments
Special thanks to:
- City of Calgary Open Data Portal for geospatial and housing data.
- Statistics Canada for providing detailed census data.
- Calgary Real Estate Board for housing market reports.
- GIS tools like QGIS and ArcGIS for map creation.

## Data Folder

transit_stations.csv 
[Transit_LRT_Stations_20241124.csv](https://github.com/user-attachments/files/17894815/Transit_LRT_Stations_20241124.csv)
- Description: Locations and attributes of transit stations in Calgary.
- Source: City of Calgary Open Data Portal.

Park_sites.csv  [Parks_Sites_20241124.csv](https://github.com/user-attachments/files/17894807/Parks_Sites_20241124.csv) 
- Description: Locations of parks in Calgary, including latitude and longitude.
- Source: City of Calgary Open Data Portal.
  
Schools_Calgary.csv
[Schools_20241124.csv](https://github.com/user-attachments/files/17894840/Schools_20241124.csv)
- Description: Locations of schools in Calgary, categorized by type (e.g., elementary, middle, high).
- Source: City of Calgary Open Data Portal.
  
## Map Folder 

map_housing_prices_near_transit.pdf: [map_housing_prices_near_transit.pdf](https://github.com/user - attachments/files/17894762/map_housing_prices_near_transit.pdf)
- A thematic map showing housing prices in Calgary with markers for transit stations.

map_parks_proximity_vs_prices.pdf: [map_parks_proximity_vs_prices.pdf](https://github.com/user-attachments/files/17894763/map_parks_proximity_vs_prices.pdf)
- A map displaying housing prices and proximity to parks.

map_schools_proximity.pdf: [map_schools_proximity.pdf](https://github.com/user-attachments/files/17894765/map_schools_proximity.pdf)
- A map showing the locations of schools and how housing prices vary nearby.

housing_prices_calculated.pdf: [housing_prices_calculated.pdf](https://github.com/user-attachments/files/17894767/housing_prices_calculated.pdf)
- A detailed thematic map of housing prices in Calgary neighborhoods.

## References
- City of Calgary Open Data Portal. (2021). Property Assessment Data. Retrieved from https://data.calgary.ca
- Calgary Real Estate Board. (2021). Housing Market Trends. Retrieved from https://www.creb.ca
- Statistics Canada. (2021). Census Data. Retrieved from https://www.statcan.gc.ca
- Fainstein, S. S. (2010). The Just City. Cornell University Press.
- Gibbons, S., & Machin, S. (2003). Valuing English primary schools. Journal of Urban Economics, 53(2), 197–219.
