# AC209-CircuityFactors-ProjectFiles-Public

iPython notebooks for the Circuity Factors Project. Four sets of files are available, which need to be run in sequence:

01 - Population - Reads population data and maps it to a grid of city 'pixels' or one-square kilometer areas

02 - OSM - Processes all road-network related information form OpenStreetMaps and maps it to each pixel. Due to their large size, the input files could not be shared through GitHub. Those can be donwloaded from https://mapzen.com/

San Francisco - Bay Area: <br>
Files used: https://www.dropbox.com/sh/5oe1xebs5h6y71y/AADB4KMUPJcamj7w8U7izsSVa?dl=0 <br>
Original source: https://mapzen.com/data/metro-extracts/metro/san-francisco-bay_california/
<br>
São Paulo:<br>
Files used: https://www.dropbox.com/sh/4cd5sy8w2me96f2/AAAZiKi8zFN5AONIhuhlkx11a?dl=0 <br>
Original source:https://mapzen.com/data/metro-extracts/metro/sao-paulo_brazil/ <br>

The files to download are the ‘GEOJSON’ files, under the ‘Datasets grouped into individual layers by OpenStreetMap tags (IMPOSM)'

03 - Real trips simulation - Generates real trips using the Google API

04 - Prediction model - Builds prediction and classification models from the data.

Codes have been set up to run independently. Output files will need to be manually moved to corresponding input file of the subsequent code. This also serves as a personal reminder to validate intermediate results.
