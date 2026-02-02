<h1>Python - Public parcels available extraction</h1>


<h2>Description</h2>
The goal of the project is to create a GPKG file containing the available public terrain of a city. Specifically, we will select the areas of the city that are not covered by : buildings, cadastral parcels, terrain with a slope of 15 degree or more, hydrographic surfaces, roads, or a 20 meters buffer around roads.
<br>
This program can be used by cities to know the public available parcels which can be use to development projects, using the parameters listed below.
<br>
The script is based on a schema created by Thibault Lecourts, my university professor in Avignon
<br />


<h2>Languages and Utilities Used</h2>

- <b>Visual Studio Code</b> 
- <b>Jupyter NoteBook</b>
- <b>Miniconda / Anaconda</b>
- <b>Python 3.10.19</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Virtual environment named "geo"</b>

<h2>How to install "geo", and the libraries </h2>

- <b>In Anaconda Prompt:</b>
- <b>/conda create -n geo python=3.10</b>
- <b>/conda activate geo</b>
- <b>/conda install geopandas rasterion shapely pandas numpy scikit-learn gdal -c conda-forge</b>
- <b>/code .</b>
<h2>Important </h2>
<br>
<br>
- <b>This project allowed me to start learning raster analysis in Python. Mainly using rasterio and GDAL. AI helped me to write, understand and learn the raster part of the script, which was previously unknow to me (GDAL and rasterio documents also helped). For the vector part, I did it with the differents documentations, and mainly with my knowledges</b>

<h2>Made on 1/25/2026 by GENTI Edwin </h2>
<h2>Program walk-through:</h2>

<p align="center">
The schema: <br/>
<img src="https://imgur.com/71uebVC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>References</h2>
- <b>LECOURT Thibault</b>

<br><br>
<b>Version française de ce projet : https://github.com/EdwinGenti/Extraction_Domaine_Public_Python</b>
