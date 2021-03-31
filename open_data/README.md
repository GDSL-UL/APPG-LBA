# Open Data Product

The result of the analysis, including the characterisation of each area as well as their trajectory available in machine-readable format for download as a CSV.

## Data Structure

**Columns:**
`LSOA11CD` - LSOA code (string)
`LSOA11NM` - LSOA name (string)
`Classification 2000` - Static classification result based on CORINE Land Cover 2000 (string)
`Classification 2006` - Static classification result based on CORINE Land Cover 2006 (string)
`Classification 2012` - Static classification result based on CORINE Land Cover 2012 (string)
`Classification 2018` - Static classification result based on CORINE Land Cover 2018 (string)
`Trajectory` - Trajecotry classification (string)
`Change` - indication whether there is a change of classification across time (boolean)
`IMD score` - Index of Multiple Deprivation score (float)
`10% IMD` - indication whether the LSOA falls within 10% most deprived areas (boolean)
`Coastal` - indication whether the LSOA falls within 10 km from the coastline as is considered a coastal area (boolean)

## License
Open Government License v3.0