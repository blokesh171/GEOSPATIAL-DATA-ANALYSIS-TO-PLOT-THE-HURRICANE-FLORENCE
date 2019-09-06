# GEOSPATIAL-DATA-ANALYSIS-TO-PLOT-THE-HURRICANE-FLORENCE
Geo spatial data to plot the path of Hurricane Florence 

    # Two packages that are popular to work with geospatial data: geopandas and Shapely.
    # Then apply these two packages to read in the geospatial data using Python and plotting the trace of Hurricane Florence from August 30th to September 18th.
    
# What is geospatial data?
    Spatial data, Geospatial data, GIS data or geodata, are names for numeric data that identifies the geographical location of a physical object such as a building, a street, a town, a city, a country, etc. according to a geographic coordinate system. From the spatial data, you can find out not only the location but also the length, size, area or shape of any object. An example of a kind of spatial data that you can get are: coordinates of an object such as latitude, longitude, and elevation. Geographic Information Systems (GIS) or other specialized software applications can be used to access, visualize, manipulate and analyze geospatial data.


# Packages requirements
     
    Pandas: provide data structures and data analysis tools
    Numpy: a fundamental package for scientific computing with Python
    SciPy:(pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering     
    RTree: a ctypes Python wrapper of libspatialindex that provides a number of advanced spatial indexing features
    GDAL: translator library for raster and vector geospatial data formats
    Fiona: Fiona reads and writes spatial data files
    Shapely: Geometric objects, predicates, and operations
    GeoPandas: extends the datatypes used by pandas to allow spatial operations on geometric types.
    PySAL: a library of spatial analysis functions written in Python intended to support the development of high-level applications.
    Matplotlib: Python 2D plotting library
    Missingno: Missing data visualization module for Python
    Install all the packages following the order above to ensure everything worked. Some packages are pre-requisites for the others, for example: to install GeoPandas, it requires Shapely, and to install Shapely; RTree, GDAL, and Fiona should be installed. The easiest way to install a package is: pip install PACKAGE_NAME

