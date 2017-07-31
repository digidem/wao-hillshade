# Digital Elevation Model (DEM) Sources

## SRTM

The most used source of DEM data is NASA's [SRTM Mission](https://www2.jpl.nasa.gov/srtm/). The data from this mission was initially limited to 90m resolution outside the USA, but in 2015 NASA released the full resolution 1 arc-second (30m) data. There are multiple versions of this data available online, but the best is void-filled "SRTM Plus" or "SRTM NASA V3" which uses ASTER GDEM2 and GMTED2010 to fill voids from clouds, prooduced under NASA's "Making Earth System Data Records for Use in Research Environments" (MEaSUREs) Program, and available from NASA's Land Processes Distributed Active Archive Center (LPDAAC): https://lpdaac.usgs.gov/dataset_discovery/measures/measures_products_table. This is available to download as `.hgt` files from https://e4ftl01.cr.usgs.gov/SRTM/SRTMGL1.003/2000.02.11/. Older Version 2 SRTM data is available as `TIF`, `BIL` and `DTED` files from the USGS: https://lta.cr.usgs.gov/SRTMVF

All these datasets are from the C-Band radar instrument from the SRTM Mission. The mission also included an X-Band Synthetic Aperture Radar (X-SAR) funded by German and Italian space agencies. This data is available from [German Aerospace Center (DLR)](http://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5515/9214_read-17716/). It is 25m resolution, but the data has large holes, resulting in a DEM which only covers thin strips: http://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5515/9214_read-17716/

Older SRTM 90m data is available from CGIAR: http://srtm.csi.cgiar.org/

## ALOS

The "Advanced Land Observing Satellite" (ALOS, or "DAICHI") was launched in 2006 by the Japan Aerospace Exploration Agency (JAXA) and captured 5m resolution DEM. A 30m "ALOS World 3D - 30m" (AW3D30) version of the data is available free-of-charge and can be downloaded from http://www.eorc.jaxa.jp/ALOS/en/aw3d30/data/index.htm. Version 1.1 released in March 2017 and is void filled with existing DEM data: http://www.eorc.jaxa.jp/ALOS/en/aw3d30/index.htm

The 5m resolution DEM from ALOS is available for purchase from [AW3D](http://www.aw3d.jp/en/), and a pricelist is here: http://www.aw3d.jp/en/pricelist/

## TanDEM-X

TanDEM-X is a public-private partnership venture between the German Aerospace Center (DLR) and Airbus Defence and Space. It launched in 2010 and captured 12m resolution DEM with 2m vertical accuracy. The dataset is available to purchase from Airbus: http://www.intelligence-airbusds.com/worlddem/ or academic institutions can request data for scientific research from [TanDEM-X Science Service System](https://tandemx-science.dlr.de/). The application form is complicated and very long.
