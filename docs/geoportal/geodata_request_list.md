
# Geodata Requests

###### This list is not used anymore, please go to /docs/geoportal/geodata-and-contributions-for-KYRBAtlas.md instead!!



###### List of geodata layers to be provided and uploaded to the MOMO geoportal
This list is meant as a living document and is not complete. Please add all data layers you want to provide to this list!


#### 1. General River Basin Characteristics
- Kharaa river basin (whole catchment)
  - *format:* shapefile
  - *data provider:* IGB
    -  -> re-uploaded to geoportal on 22.01.2016, 17:31h by [V. Bremerich](https://github.com/vanbremer) (IGB)
    -  file name: 01_kharaa_river_basin_32648.shp
    -  suggested layer name: "Kharaa River Basin"
    -  suggested position in layer tree: 
      - Themenmodul 1: Hydrologie, Landnutzung
        - Einzugsgebiet Kharaa

  - Kharaa river basin subbasins (updated version 2016)
    - slight changes at the outlets of individual subbasins to eliminate artifacts at the intersection of river network and subbasin boundaries (subbasins where derived from a DEM while the river network was digitised with a higher resolution from topographical maps, subbasins need to be adapted to match the river network at river junctions)
    - *format:* shapefile
    - *data provider:* IGB
      -  -> uploaded to geoportal on 19.01.2016, 14:07h by [V. Bremerich](https://github.com/vanbremer) (IGB)
      -  file name: 01_kharaa_subbasins_32648.shp
      -  suggested layer name: "Kharaa Subbasins"
      -  suggested position in layer tree: 
        - Themenmodul 1: Hydrologie, Landnutzung
  	      - Einzugsgebiet Kharaa
  	      - to replace the existing layer "Kharaa Subasins"
  
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
- Surface water body types (updated version 2016
  - new version 2016: attribute table edited and some invalid geometries corrected
  - *format:* shapefile
  - *data provider:* IGB
    - for a detailed description see this open access publication: [http://www.mdpi.com/2073-4441/7/7/3166](http://www.mdpi.com/2073-4441/7/7/3166)
    -  -> uploaded to geoportal on 19.01.2016, 12:20h by [V. Bremerich](https://github.com/vanbremer) (IGB)
    -  file name: 02_surface_water_bodies_corr_32648
    -  suggested layer name: "Surface Water Bodies"
    -  suggested position in layer tree: 
      - Themenmodul 1: Hydrologie, Landnutzung
        - Einzugsgebiet Kharaa

#### 3. Groundwater Resources

- groundwater bodies
  - *format:* shapefile
  - *data provider:* IGB
    - *this layer still needs some editing, will be uploaded to the geoportal in the coming weeks!*
    - file name: 03_groundwater_bodies_32648.shp
    - suggested layer name: "Groundwater Bodies"
    - suggested position in layer tree: 
      - Themenmodul 1: Hydrologie, Landnutzung
        - Einzugsgebiet Kharaa

- groundwater monitoring sites
  - *format:* shapefile
  - *data provider:* IGB
  -  -> uploaded to geoportal on 19.01.2016, 18:05h by [V. Bremerich](https://github.com/vanbremer) (IGB)
    - file name: 03_groundwater_monitoring_sites_32648.shp
    - suggested layer name: "Groundwater Monitoring Sites"
    - suggested field for styling: "WB_CODE"
    - suggested position in layer tree: 
      - Themenmodul 1: Hydrologie, Landnutzung
        - Einzugsgebiet Kharaa

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

- initial risk assessment of surface water bodies
  - *format:* shapefile
  - *data provider:* IGB
    - for a detailed description see this open access publication: http://www.mdpi.com/2073-4441/7/7/3166
    -  -> uploaded to geoportal on 21.01.2016, 12:15h by [V. Bremerich](https://github.com/vanbremer) (IGB)
    - file name: 07_risk_assessment_surface_water_bodies_32648.shp
    - suggested layer name: "Initial Risk Assessment of Surface Water Bodies"
    - suggested field for styling: "RISK_LEVEL" (not at risk / possibly at risk / at risk) 
    - suggested position in layer tree: 
      - Themenmodul 2: Gewässerökologie und -qualität
        - Changing environment and human impact

- initial risk assessment of groundwater bodies
  - *format:* shapefile
  - *data provider:* IGB
    - for a detailed description see this publication: "Groundwater quality under stress: contaminants in the Kharaa River basin (Mongolia)", http://link.springer.com/article/10.1007%2Fs12665-014-3148-2
    - this layer still needs some editing, will be uploaded to the geoportal in the coming weeks
    - file name: 07_risk_assessment_groundwater_bodies_32648.shp
    - suggested layer name: "Initial Risk Assessment of Groundwater Bodies"
    - suggested position in layer tree: 
      - Themenmodul 2: Gewässerökologie und -qualität
        - Changing environment and human impact

  - nutrient emissions
    - *format:* shapefile
    - *data provider:* IGB
    
  - pollution hot spots
    - e.g gold mines, waste water treatment plants, contaminated areas
    - *format:* shapefile
    - *data provider:* IGB
      - **Mining Operations**
        -  -> re-uploaded to geoportal on 22.01.2016, 17:48h by [V. Bremerich](https://github.com/vanbremer) (IGB)
        -  file name: 07_mining_operations_32648.shp (POINT)
        -  suggested layer name: "Mining operations"
        -  suggested position in layer tree: 
          - Themenmodul 2: Gewässerökologie und -qualität
    	      - Changing environment and human impact
      - **Potentially contaminated areas**
        -  -> re-uploaded to geoportal on 22.01.2016, 17:58h by [V. Bremerich](https://github.com/vanbremer) (IGB)
        -  file name: 07_potentially_contaminated_areas_32648.shp (POINT)
        -  suggested layer name: "Potentially contaminated areas"
        -  suggested position in layer tree: 
          - Themenmodul 2: Gewässerökologie und -qualität
    	      - Changing environment and human impact
