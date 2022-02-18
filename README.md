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

