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

## Download Instructions
1. On GitHub.com, navigate to the main page of the repository.
2. To the right of the list of files, click Releases.

![image](https://user-images.githubusercontent.com/41050589/157262044-1c72d164-fd9a-4783-a1e7-e3fc5a48ee73.png)

3. Click on the latest ENVIToolkit archive (i.e. ENVIToolkit_PRISMA_v1.0.zip) 

![image](https://user-images.githubusercontent.com/41050589/157260447-e8198929-eccd-4810-840b-a72527d07151.png)


## Installation Instructions (option 1)
To install the software unzip the latest release (i.e. ENVIToolkit_PRISMA_v1.0.zip) on your ENVI installation folder (i.e. C:\Program Files\Harris\ENVI56).

## Installation Instructions (option 2)
- Unzip the latest release (i.e. ENVIToolkit_PRISMA_v1.0.zip) in a temporary folder (i.e C:\tmp\ENVIToolkit_PRISMA_v1.0).
- Copy the three extracted folder (custom_code, extensions, save) in ENVI installation folder (i.e. C:\Program Files\Harris\ENVI56)

## Verify installation
After installation you will be able to see the new tasks on ENVI Toolbox, as below.
 
![image](https://user-images.githubusercontent.com/41050589/154697039-e82d1b48-bc08-4752-9eb4-a716b0df1a0d.png)

## PRISMA MISSION
Further information can be found in ASI internet site [PRISMA MISSION](https://www.asi.it/en/earth-science/prisma/)
