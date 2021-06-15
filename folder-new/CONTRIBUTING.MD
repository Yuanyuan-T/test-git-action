# Contribute Instruction

Hellow, triplification contributors! 

Please follow this structure to contribute. Notice the folder naming scheme is consistent with https://github.com/KnowWhereGraph/kwg-seed-graph/tree/master/schemas as `name-of-dataset-source`, For example, Storms-NOAA.


## root/

- README.MD

- CONTRIBUTING.MD
  
- **data**
    - raw-data
        - Storms-NOAA
        - SmokePlumes-NOAA
        - CropLandTypes-USDA
        - Expertise-KWG&DR 
        - DisasterDeclaration-FEMA
        - HistoricalFires-USGS
        - Earthquakes-USGS
        - USClimateDivisions-NOAA
        - SoilTypes-SSURGO
        - ...
    - output (these folders should have EXACTLY the same name as their source folders)
        - Storms-NOAA
        - SmokePlumes-NOAA
        - CropLandTypes-USDA
        - ...
- **code** (these folders should have EXACTLY the same name as their dataset folder)
    - util.py (anyone can contribute -- if you do COMMENTING THOROUGHLY is 1000000% REQUIRED :) )
    - variable.py (anyone can contribute)
    - Storms-NOAA
        - README.MD (REQUIRED) 
            - how to preprocess 
            - how to re-run your code
            - any used external libraries 
            - ...
        - "you can do whatever you want in here, the world is your oyster"
     - SmokePlumes-NOAA 
     - CropLandTypes-USDA
     - ...

- **use-case-1**: Direct Relief. [Index the questions carefully and refer back to https://www.dropbox.com/sh/l98ldifvowc9sp4/AAARLJNvnZ6K9Bp6P7RN4A21a?dl=0]

- **use-case-2**: Farm2Table 

- **use-case-3**: FMI (Food Security) --> no competency questions yet. 
