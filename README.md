![GitHub Dark](img/logo_white.svg#gh-dark-mode-only)
![GitHub Light](img/logo_blue.svg#gh-light-mode-only)

# London (EGTT) & Scottish (EGPX) FIR Sector File
:wave: An official community driven sector file for IVAO's Aurora software covering the London (EGTT) and Scottish (EGPX) FIRs.

+ https://wiki.ivao.aero/en/home/devops/manuals/SectorFile_Definition
+ https://wiki2.xu.ivao.aero/en/atc/sectorfile/getting-started

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

+ Boundary/grass outline - emcompass the entire airfield with this
+ Aprons
+ Parking positions
+ Taxiways
+ Runways
+ Taxiway lines
+ Stop bar lines

You do not need to add taxiway or holding point labels.

### Contribution Agreement
By contributing to this repository you agree that the ownership of any alteration(s) and/or addition(s) you make are transferred to IVAO United Kingdom & Ireland in its entirety and cannot be recalled.

## To Do
In no particular order...

1) [x] <strike>Find lower resolution GEO boundary</strike>
2) [ ] Change coordinate format to Decimal format
3) [x] <strike>Add airway structures</strike>
4) [x] <strike>Use poly fill/line to show airway/CAS structure for airspace when an area unit is online</strike>
5) [x] <strike>[Add poly fill/line to show when external area units are online][i3]
6) [x] <strike>[Fix ATC high/low sector boundaries to match up perfectly][i4]
7) [ ] [Add gate size information to gates file][i5] (https://wiki.ivao.aero/en/home/devops/manuals/SectorFile_Definition#gates-gates-information)
8) [x] <strike>[High and low airways are missing points outside the UK FIR][i6]</strike>
9) [x] <strike>Add VFR reporting points on a per-airport basis</strike>
10) [x] <strike>Alter Alderney island so that it is higher fidelity

More issues, changes and improvements can be found in the issues section.
