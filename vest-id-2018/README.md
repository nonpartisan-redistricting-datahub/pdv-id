# pdv-id
Partner data validation for Idaho, from VEST 2018. 

Our final validation report for this dataset is available [here](). [In progress]

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
- File: Election results, 2018 
  - Online: https://sos.idaho.gov/elections-division/election-results/
  - Source: ID Secretary of State
  - File name: `18gen_stwd_pct.xls` (available upon request)
  - Accessed: 5/20/2021

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
  - Note: not finding any precinct maps or GIS department on the county site. 
- Madison
  - Link: https://www.co.madison.id.us/departments/elections/65-august-28-2018-election-precinct-voting-location-map
  - Note: found a 2018 PDF map that looks like it was made from a shapefile. There is a GIS department. 
- Minidoka
  - Link: https://www.minidoka.id.us/178/Voting-Precincts
  - Note: finding precinct maps that were made from a shapefile, there is contact information for Auditor and GIS consultants. 
- Nez Perce
  - Link: https://www.co.nezperce.id.us/Elected-Officials/Clerk-Auditor/Elections/Precinct-List
  - Note: PDF map available on the right side of this page. 
- Oneida
  - Note: not finding any precinct maps or GIS department on the county site. 
- Power
  - Link: https://www.co.power.id.us/power-county-clerk-auditor-recorder/precinct-and-taxing-district-maps/
  - Note: PDF map available. 
- Twin Falls
  - Link: https://twinfallscounty.org/wp-content/uploads/TFCo-Legislative-Districts-002.pdf
  - Note: PDF map available. 
- Valley
  - Link: http://www.co.valley.id.us/departments/election-information/, click Taxing District/Voting Info under online maps to get to https://valleycounty.maps.arcgis.com/apps/webappviewer/index.html?id=34244a0b84f64fb880dd9b4a29b146d8
  - Note: it seems like the City Precincts and County Precincts show maps for the 7 precincts in Valley County, but there is no shapefile available to download. 


## Processing
`id_vest_2018.ipynb`: validation script & comments for report