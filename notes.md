https://gdal.org/programs/gdal2tiles.html
https://gdal.org/programs/gdal2tiles.html#cmdoption-gdal2tiles-p

Starting with GDAL 3.2, additional profiles are available from tms_XXXX.json files placed in GDAL data directory
/usr/share/gdal/

gdal2tiles.py --xyz -x -s EPSG:3035 --zoom=0-8 --processes=2 /home/juju/Bureau/gisco/elevation/EU_DEM_mosaic_1000K/1000_temp.vrt /home/juju/Bureau/aaa/

gdal2tiles.py -p EUR --xyz --zoom=0-5 -x -s EPSG:3035 --processes=3 /home/juju/Bureau/gisco/map_background/map.png /home/juju/Bureau/aaa/
gdal2tiles.py -p EUR --xyz --zoom=0-8 -x -s EPSG:3035 --processes=3 /home/juju/Bureau/gisco/map_background/map.png /home/juju/Bureau/aaa/

level 7 resolution:
scale 1:800 000
211.6673615 m/pix
211.6735723 m/pix
-> 211.7 m/pix
