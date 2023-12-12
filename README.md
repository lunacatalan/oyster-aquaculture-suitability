# Analysis of Oyster Aquaculture Suitability
This project investigated the potential for oyster marine aquaculture in the Exclusive Economic Zones of the West Coast, US

## Goals

-   Determine the suitability area in the Exclusive Economic Zones of
    the West Coast
-   Illustrate what EEZ have the greatest percentage and area for
    suitable marine aquaculture
-   Create workflow to determine suitable marine aquaculture area for
    other species

## Visualizations

This project will have two visualizations in the `.RMD` file that
pertain to the analysis, and one that uses the function created at the
end of the analysis. The first shows the EEZ by **percent** of suitable
area for oyster marine aquaculture, and the second shows the EEZ by
**total area** of suitable area for oyster marine aquaculture. The final
visualization is a map of both the percent and the total area in the
Exclusive Economic Zones for the test species (eg. Clams).

## Skills Highlights

-   combining vector and raster data
-   resampling raster data
-   masking raster data
-   map algebra

Contents/Structure:


    oyster-aquaculture-suitability
        │ README.md 
        │ Rmd/Proj files
        │ 
        └───data 
             │ wc_regions_clean.shp 
             │ depth.tif 
             │ average_annual_sst_2008.tif 
             │ average_annual_sst_2009.tif
             │ average_annual_sst_2010.tif
             │ average_annual_sst_2011.tif 
             │ average_annual_sst_2012.tif

Data Download Instructions:

**IMPORTANT** The data associated with this assignment is too large to
include in the GitHub repo. Data should be stored locally and added to
.gitignore file. Download data from
[here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing).
