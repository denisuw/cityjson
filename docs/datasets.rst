================
Example datasets
================


.. contents:: :local:

Dummy file showcasing the different possibilities
-------------------------------------------------

-  :download:`download example.json <../example-datasets/dummy-values/example.json>`

Dummy means that the values of the coordinates have no value, this is just to see how a file could look like with different possibilities of CityJSON.



Several cities around the world
-------------------------------

.. note::
  The files below were *automatically* converted from CityGML with the open-source library `citygml4j <https://github.com/citygml4j/citygml4j>`_.


.. list-table:: 
   :header-rows: 1
   :widths: 10 12 15 20 8
   :stub-columns: 1

   *  -  CityGML dataset
      -  CityJSON+CityGML download
      -  screenshot
      -  details
      -  textures
   *  -  `Den Haag <https://data.overheid.nl/data/dataset/ngr-3d-model-den-haag>`_
      -  `DenHaag.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/DenHaag/DenHaag.zip>`_     
      -  .. image:: _static/dataset_denhaag.png
            :width: 100%      
      -  'Tile 01', Buildings (in LoD2) and Terrain are merged
      -  no
   *  -  `Montréal <http://donnees.ville.montreal.qc.ca/dataset/maquette-numerique-batiments-citygml-lod2-avec-textures/resource/36047113-aa19-4462-854a-cdcd6281a5af>`_
      -  `Montreal.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/Montreal/Montreal.zip>`_  
      -  .. image:: _static/dataset_montreal.png
            :width: 100%      
      -  tile 'VM05'. Buildings in LoD2
      -  no
   *  -  `New York <https://www1.nyc.gov/site/doitt/initiatives/3d-building.page>`_
      -  `NewYork.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/NewYork/NewYork.zip>`_     
      -  .. image:: _static/dataset_newyork.png
            :width: 100%      
      -  tile 'DA13'. Buildings in LoD2
      -  no
   *  -  `Rotterdam <http://rotterdamopendata.nl/dataset/rotterdam-3d-bestanden/resource/edacea54-76ce-41c7-a0cc-2ebe5750ac18>`_
      -  `Rotterdam.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/Rotterdam/Rotterdam.zip>`_
      -  .. image:: _static/dataset_rotterdam.png
            :width: 100%      
      -  neighbourhood 'Delfshaven'. Buildings in LoD2
      -  yes
   *  -  `Vienna <https://www.data.gv.at/katalog/dataset/86d88cae-ad97-4476-bae5-73488a12776d>`_
      -  `Vienna.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/Vienna/Vienna.zip>`_     
      -  .. image:: _static/dataset_vienna.png
            :width: 100%      
      -  Buildings in LoD2
      -  no
   *  -  `"GeoRes" <https://www.citygml.org/samplefiles/>`_
      -  `GeoRes.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/GeoRes/GeoRes.zip>`_     
      -  .. image:: _static/dataset_geores.jpg
            :width: 100%
      -  CityGML demo. Buildings, Terrain, Vegetation, Water, LandUse. 
      -  yes
   *  -  `"Railway" <https://www.citygml.org/samplefiles/>`_
      -  `Railway.zip <https://3d.bk.tudelft.nl/opendata/cityjson/v08/Railway/Railway.zip>`_ 
      -  .. image:: _static/dataset_railway.jpg
            :width: 100%      
      -  CityGML demo. Buildings, Railway, Terrain, Vegetation (with Implicit Geometries), Water, Tunnels
      -  yes


.. _compression_factors:

CityJSON compression factors 
----------------------------

.. list-table:: 
   :header-rows: 1
   :stub-columns: 1

   *  -  CityGML dataset
      -  CityGML size
      -  CityGML size (w/o spaces)
      -  CityJSON
      -  compression factor
    
   *  -  Den Haag
      -  23MB 
      -  18MB 
      -  2.9MB 
      -  6.2
   *  -  Montréal
      -  56MB 
      -  42MB 
      -  5.4MB 
      -  7.8
   *  -  New York
      -  590MB 
      -  574MB 
      -  105MB 
      -  5.5
   *  -  Rotterdam
      -  16MB 
      -  15MB 
      -  2.6MB 
      -  5.8
   *  -  Vienna
      -  37MB 
      -  36MB 
      -  5.3MB 
      -  6.8 
   *  -  "GeoRes"
      -  4.3MB 
      -  4.1MB 
      -  524KB 
      -  8.0
   *  -  "Railway"
      -  45MB 
      -  34MB 
      -  4.3MB 
      -  8.1 

.. note:: 

   - Observe that the file size doesn't take into account the size of the textures files (PNG, JPG, etc) since CityJSON refers to the same ones. 
   - 'w/o spaces' means that CityGML files have all the carriage returns, tabs and spaces removed with `this script <https://gist.github.com/hugoledoux/acc66a41b2262ff9b8efb7cf515440f9>`_, for a fair estimation of the compression factor
   
