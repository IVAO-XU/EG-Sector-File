![GitHub Dark](img/logo_white.svg#gh-dark-mode-only)
![GitHub Light](img/logo_blue.svg#gh-light-mode-only)

# London (EGTT) & Scottish (EGPX) FIR Sector File
:wave: An official community driven sector file for IVAO's Aurora software covering the London (EGTT) and Scottish (EGPX) FIRs.

+ https://wiki.ivao.aero/en/home/devops/manuals/SectorFile_Definition

## Features
+ :hourglass: **Faster loading time thanks to a less intricate coastline.**  
*Reduced from 230,000 lines to 6,000 line of codes, a 97.4% decrease with no loss of quality.*
+ :world_map: **Airways and end point fixed**  
*Removing those random waypoints that displayed when viewing a pilot's route.*
+ :door: **Complete SIDs/ STARs**  
*Detailed SIDs and STARs for all airports comprehensively drawn.*

## How to Contribute
### Overview
Any member of the community may contribute this sector file so long as:
+ The data provided is factual and realistic.

### Adding airports layouts ("SMRs")
Ground layouts can be created by anyone simply by using Google Earth's polygon and line tools.

Create each feature of the airport individually in the following order, first = lowest:

+ Boundary/grass outline - (encompass the entire airfield with this)
+ Parking positions
+ Taxiways
+ Runways
+ Aprons
+ Buildings
Polygon drawings create the PLF file

+ Stands lines
+ Taxiway lines
+ Stop bar lines
Create the GEO file

You do not need to add taxiway or holding point labels as these are stored in separate files

### Contribution Agreement
By contributing to this repository you authorise that the ownership of any ammendment(s) and/or addition(s), become the intellectual property of IVAO United Kingdom & Ireland MCD.
