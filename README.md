# Modeled Annual Energy Consumption for Office Buildings in Toronto

Please click on the link below to vew an interactive map of the modeled data for office buildings in Toronto.

https://a-sharma06.github.io/toronto-annual-office-energy/

# Description

As sustainable planning and resilience become more widespread concers of urban administrations, it is important that information about energy cosnumption is easily accessible. However, currently there are very few cities which provide open energy data.

This project uses a linear regression model to estimate the annual energy consumption by office buildings in Toronto. This project uses 3 publically available datasets to create a statistical model between annual energy consumption and total floor area.

Model Used: log(Total_Energy_kWh) ~ log(AVG_HEIGHT*SHAPE_AREA)

Where,

Total_Energy_kWh = Annual Energy Consumption in kWh

AVG_HEIGHT = Average Building Height, obtained from 3D Massing Data

SHAPE_AREA =  Building Footprint Area in Square Meters, obtained from 3D Massing Data

These datasets are:
1. Energy use and greenhouse gas emissions for the Broader Public Sector: https://www.ontario.ca/data/energy-use-and-greenhouse-gas-emissions-broader-public-sector
2. Address Points (Municipal) - Toronto One Address Repository: https://www1.toronto.ca/wps/portal/contentonly?vgnextoid=91415f9cd70bb210VgnVCM1000003dd60f89RCRD
3. Toronto 3D Massing Data- https://www1.toronto.ca/wps/portal/contentonly?vgnextoid=d431d477f9a3a410VgnVCM10000071d60f89RCRD





