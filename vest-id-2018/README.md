# pdv-id
Partner data validation for Idaho, from VEST 2018. 

Our final validation report for this dataset is available [here](). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source

### Accessible files
- File: VEST Idaho, 2018
  - Online: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/DFEQHK&version=36.0
  - Source: VEST, Harvard Dataverse
  - File name: `id_2018.zip` (available upon request)
  - Accessed: 5/18/2021
  - Documentation file: 
    - Online: https://dataverse.harvard.edu/file.xhtml?fileId=4499066&version=36.0
    - File name: `documentation.txt`
    - Accessed: 5/18/2021
- File: Precinct shapefiles, 2019 
  - Online: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st16_id.html
  - Source: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Accessed: 5/18/2021
- File: Election results, 2018 (cleaned)
  - Online: https://github.com/MEDSL/2018-elections-official
  - Source: MIT Election Data and Science Lab
  - File name: `precinct_2018.zip` (available upon request)
  - Accessed: 2/3/2021
  - Note: this file is not listed by VEST. 

### Inaccessible files

### Notes

Tracking down county shapefiles, the following links were all accessed on 5/18/2021:  
- Ada
  - Link: https://adacounty.id.gov/elections/maps/#Precinct_Maps 
  - Note: PDFs of precinct by precinct maps
- Adams
  - Link: https://co.adams.id.us/departments/clerk-auditor-recorder/election-information/polling-places/
  - Note: PDF of county-wide precinct map
- Bannock
  - Link: https://bannock.maps.arcgis.com/home/index.html 
  - Note: Navigate to Elections Kiosk. Not finding a downloadable shapefile. 
- Bingham
  - Link: https://www.co.bingham.id.us/bingham_county_gis_mapping/interactive_gis.html
  - Note: Navigate to Voting Mapping. Not finding a downloadable shapefile. 
- Boise
  - Link: https://boisecounty.us/services/elections/
  - Note: Click Boise County Precinct Map on the right, that takes you to a PDF map
- Bonner
  - Link: https://cloudgis.bonnercountyid.gov/portal/home/index.html
  - Note: Navigate to Elections Polling Place Locator. Not finding a downloadable shapefile. 
- Cassia
  - Link: https://www.cassiacounty.org/Election-Maps
  - Note: Lots of PDF maps, but no 2018 maps and no shapefiles. 
- Clearwater
  - Link: https://www.clearwatercounty.org/departments/gis_and_mapping/web_map_layers.php
  - Note: Has a GIS department and lists Voting Precincts, but does not link to anywhere. 
- Custer
  - Note: not finding any precinct maps or GIS department on the county site. 
- Fremont
  - Link: https://www.co.fremont.id.us/departments/planning_building/gis/index.htm
  - Note: found a GIS manager and list of polling locations, but no maps. 
- Jefferson
  - Link: http://www.co.jefferson.id.us/use_images/Elections/2018precinctmap2.pdf
  - Note: found a 2018 PDF map that looks like it was made from a shapefile. There is a GIS department. 
- Kootenai
  - Link: https://www.kcgov.us/319/Individual-Precinct-Maps
  - Note: PDFs of precinct maps. 
- Latah
  - Link: https://www.latah.id.us/auditor/elections/, navigate to Latah County Precinct Map on the right to get to https://api.latah.id.us/web/DownloadFileEx?filename=Official%20Voter%20Precinct.pdf
  - Note: Only finding PDF map. 
- Lemhi
  - Note: not finding any precinct maps or GIS department on the county site. 
- Lewis
  - Link: 
  - Note: 
- Madison
  - Link: 
  - Note: 
- Minidoka
  - Link: 
  - Note: 
- Nez Perce
  - Link: 
  - Note: 
- Oneida
  - Link: 
  - Note: 
- Power
  - Link: 
  - Note: 
- Twin Falls
  - Link: 
  - Note: 
- Valley
  - Link: 
  - Note: 


## Processing
`id_vest_2018.ipynb`: validation script & comments for report