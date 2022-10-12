# R

  Beautiful maps in R
  
  Spatial viz



## 1. [Earth at Night](https://github.com/NdutaCharity/R/blob/main/Raster-on-globe.R)

    This is a fun map of the earth at night on R using  NASA’s Black Marble data to display the shiny lights on the globe
    with guidance from @Milos Popovic.
    
    Who doesn't love some dark and light (pun intended by all means 😉😉)
    
        "By removing natural and stray light sources,
        researchers have provided a clearer picture of the human footprint on Earth 
        and opened up new opportunities in    disaster response, demographics, and applied research." 
        (https://earthobservatory.nasa.gov/features/NightLights)
    
   ### Libraries used
         "tidyverse", "sf", "giscoR", "mapview", "terra", "terrainr", "magick"
         
         tidyverse and sf for spatial analysis and data wrangling; 
         giscoR for importing the world shapefile; 
         terra for manipulating raster data; 
         terrainr for plotting a multi-band raster; 
         magick for map annotation.
   ### Projections
         1. standard longitude/latitude
                  To project our map to WGS84
                  
         2. [Azimuthal orthographic](https://proj.org/operations/projections/ortho.html)
                  To turn the flat Earth into a globe.
         
