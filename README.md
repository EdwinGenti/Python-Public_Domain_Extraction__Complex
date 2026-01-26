<h1>Python - Public Domain Extraction</h1>


<h2>Description</h2>
Le but du projet est de créer un fichier au format GPKG contenant les terrains publics disponibles d'une ville. En somme, récupère les terrains d'une commune qui ne superposent pas : les bâtiments, le cadastre, les terrains où la pente est supérieure à 15 degrès, les surfaces hydrographiques, les routes ainsi qu'une zone tampon de 20 mètres autour des routes
<br>
<br>
The goal of the project is to create a GPKG file containing the available public terrain of a city. Specifically, we will select the areas of the city that are not covered by : buildings, cadastral parcels, terrain with a slope of 15 degree or more, hydrographic surfaces, roads, or a 20 meters buffer around roads.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Visual Studio Code</b> 
- <b>Jupyter NoteBook</b>
- <b>Miniconda / Anaconda</b>
- <b>Python 3.10.19</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Virtual environment named "geo"</b>

<h2>Environments Used </h2>

- <b>How to install "geo", and the libraries</b>
- <b>In Anaconda Prompt:</b>
- <b>/conda create -n geo python=3.10</b>
- <b>/conda activate geo</b>
- <b>/conda install geopandas rasterion shapely pandas numpy scikit-learn gdal -c conda-forge</b>

<h2>Important </h2>
- <b>Ce projet m'a permis de commencer à apprendre l'analyse raster en Python, notamment via rasterio et GDAL. L'IA m'a aidé et m'a permis d'apprendre la partie raster, qui m'était encore inconnue sur Python (Les documentations GDAL et rasterio m'ont également aidées). Quant à la partie vecteur, je l'ai effectuée via la documentation des différentes bibliothèques, et surtout avec mes acquis</b>
<br>
<br>
- <b>This project allowed me to start learning raster analysis in Python. Mainly using rasterio and GDAL. AI helped me to write, understand and learn the raster part of the script, which was previously unknow to me (GDAL and rasterio documents also helped). For the vector part, I did it with the differents documentations, and mainly with my knowledges</b>

<h2>Made on 1/25/2026 by GENTI Edwin </h2>
<h2>Program walk-through:</h2>

<p align="center">
The schema: <br/>
<img src="https://imgur.com/71uebVC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


