# PRISMAToolkit
PRISMA Toolkit for ENVI

ENVI PRISMA Toolkit contains the following 5 tasks:
* Refine RPCs (HDF-EOS5)
  - Improves Geolocation with Reference Image(s) from .he5
* Refine RPCs (ENVI Raster)
  - Improves Geolocation with Reference Image(s) from ENVI Raster (binary file + .hdr)
* Build HSI Cube
  - Glues the VNIR and SWIR dataset removing the redundant wavelengths
* Reproject with GLT
  - Reprojects the PRISMA dataset using the Geographic Lookup Table
* Inherits RPCs
  - Copy RPC coefficients from an ENVI Raster

## Installation Instructions
To install the software unzip the latest release (i.e. ENVIToolkit_PRISMA._v1.0.zip) on your ENVI installation folder (i.e. C:\Program Files\Harris\ENVI56).
After inslattation you will be able to see the new task on ENVI Toolbox, as below.
 
![image](https://user-images.githubusercontent.com/41050589/154697039-e82d1b48-bc08-4752-9eb4-a716b0df1a0d.png)

## PRISMA MISSION
Further information about PRISMA MISSION can be found in ASI internet site [PRISMA MISSION] (https://www.asi.it/en/earth-science/prisma/)
