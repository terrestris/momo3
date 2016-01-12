
#Geodata Requests

######List of geodata layers to be provided and uploaded to the MOMO geoportal
This list is meant as a living document and is not complete. Please add all data layers you want to provide to this list!


####1. General River Basin Characteristics
  - Kharaa river basin (whole catchment)
    - *format:* shapefile
    - *data provider:* IGB
      -  -> uploaded to geoportal on 17.12.2015, 17:31h by [V. Bremerich](https://github.com/vanbremer) (IGB)
      -  file name: kharaa_basin.shp
      -  suggested layer name: "Kharaa Basin"
      -  suggested position in layer tree: 
        - Themenmodul 1: Hydrologie, Landnutzung
  	      - Einzugsgebiet Kharaa

  - Kharaa river basin subbasins (updated version 2016)
    - slight changes at the outlets of individual subbasins to eliminate artifacts at the intersection of river network and subbasin boundaries (subbasins where derived from a DEM while the river network was digitised with a higher resolution from topographical maps, subbasins need to be adapted to match the river network at river junctions)
    - *format:* shapefile
    - *data provider:* IGB
      - for a detailed description see this open access publication: [http://www.mdpi.com/2073-4441/7/7/3166](http://www.mdpi.com/2073-4441/7/7/3166)
      -  -> uploaded to geoportal on 12.01.2016, 16:17h by [V. Bremerich](https://github.com/vanbremer) (IGB)
      -  file name: 02_surface_water_bodies_32648
      -  suggested layer name: "Surface Water Bodies"
      -  suggested position in layer tree: 
        - Themenmodul 1: Hydrologie, Landnutzung
  	      - Einzugsgebiet Kharaa
  
  - Administrative borders
    - AIMAG and SOUM boundaries
    - *format:* shapefile
    - *data provider:* IGB
      - suggested data source for AIMAG boundaries: [Environmental Information Center Mongolia] (http://www.eic.mn/geodataen/download.html) http://www.eic.mn:8080/geonetwork/srv/eng/resources.get?id=54&fname=aimagbnd.rar&access=private
  
  - Land cover
    - Landsat 5 TM classification 1989, 2005
    - Kharaa land use classification 2006
    - Kharaa land use classification 2010
    - *format:* raster
    - *data provider:* UFZ
    
  - Soil loss
    - Kharaa soil loss map
    - *format:* raster
    - *data provider:* UFZ
  
####2. Surface Water Resources
  - Surface water body types
    - *format:* shapefile
    - *data provider:* IGB

####3. Groundwater Resources
  - groundwater bodies
    - *format:* shapefile
    - *data provider:* IGB
    
####4. Land Use and Socioeconomy

####5. Water Demand, Water Balance and Wastewater Treatment

####6. Environmental monitoring
  - meteorological stations
    - *format:* shapefile (point)
    - *data provider:* UFZ?
    
  - water quality stations
    - *format:* shapefile (point)
    - *data provider:* IGB
    
  - groundwater quality stations
    - *format:* shapefile (point)
    - *data provider:* IGB
    
  - remote sensing
    - *format:* raster
    - *data provider:* HTW

####7. Changing environment and human impact
  - human impact on surface water quality (water bodies)
    - *format:* shapefile
    - *data provider:* IGB
    
  - human impact on groundwater quality (groundwater bodies)
    - *format:* shapefile
    - *data provider:* IGB
    
  - nutrient emissions
    - *format:* shapefile
    - *data provider:* IGB
    
  - pollution hot spots
    - e.g gold mines, waste water treatment plants, contaminated areas
    - *format:* shapefile
    - *data provider:* IGB
