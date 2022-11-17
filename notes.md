//https://gdal.org/programs/gdal2tiles.html
gdal2tiles.py --xyz -x -s EPSG:3035 --zoom=0-7 --processes=2 /home/juju/Bureau/gisco/elevation/EU_DEM_mosaic_1000K/1000_temp.vrt /home/juju/Bureau/aaa/

https://raw.githubusercontent.com/jgaffuri/mbxyz/main/pub/test/3/4/2.png

https://gdal.org/programs/gdal2tiles.html#cmdoption-gdal2tiles-p



 <?xml version="1.0" encoding="UTF-8" ?>
  <TileMap version="1.0.0" tilemapservice="http://tms.osgeo.org/1.0.0">
   <Title>British Columbia Landsat Imagery (2000)</Title>
   <Abstract>Landsat data collected in the year 2000 over British Columbia.</Abstract>
 | <KeywordList></KeywordList>
 | <Metadata type="TC211" mime-type="text/xml" href="http://www.org" />
 | <Attribution>
 |   <Title>Government of British Columbia</Title>
 |   <Logo width="10" height="10" href="http://gov.bc.ca/logo.png" mime-type="image/png" />
 | </Attribution>
 | <WebMapContext href="http://wms.gov.bc.ca" />
   <SRS>EPSG:3005</SRS>
   <BoundingBox minx="100000" miny="100000" maxx="1800000" maxy="1800000" />
   <Origin x="100000" y="100000" />
   <TileFormat width="256" height="256" mime-type="image/png" extension="png" />
   <TileSets profile="local">
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/2048" units-per-pixel="2048" order="0" />
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/1024" units-per-pixel="1024" order="1" />
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/512" units-per-pixel="512" order="2" />
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/256" units-per-pixel="256" order="3" />
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/128" units-per-pixel="128" order="4" />
     <TileSet href="http://tms.osgeo.org/1.0.0/landsat2000/64" units-per-pixel="64" order="5" />
   </TileSets>
 </TileMap>

