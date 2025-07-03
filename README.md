# Third-Year-Project

The title of the project is "Classifying & Examining Deforestation Patterns & its Environmental Implications"

Non-Forestry activites including mining, industries, railways etc have the potential to impact the ecological and environmental balance. Maharashtra being the second most industrializes state in India has been affected by deforestation both environmentally and socioeconomically. Therefore this project aims to classify the forested and deforested areas.

Two pahses were accomplished in the development of this framework. Phase 1: Lancover Sentinel-2 Satellite images from ESRI were collected over the years 2017-2022 for 36 district of Maharashtra. For this phase Siamese Neural Network algoritm was applied to detect the changes in the images. The image compromised of Water, Trees, Crops, Built Area, Bare ground, Flooded Vegetation, Snow/Ice, Clouds, Rangeland. Firstly, a python script was run over the imaged to extarct th green pixels, after this the iamges were resized, and finally the algorithm was run over these images[ (2017 & 2019), (2018 & 2020), (2020, 2022)].If there was a decrease in the green pixel intensity, the area was classified as Deforested and an increase in the green pixel intensity results to a forested area.

Since Phase 1 was already implemented in various existing studies, Phase 2 which is the innovatie part of the project was implemented. Phase 2 consists of variois geo-spatial factors that were the leading cause to deforestation. Factours such as Building Footprints, Elevation Data, Forest Fire, Distance To Roads were collected. Additional, green pixel counts were also included from phase 1. All the numerical factors were fed into the Ada Boost. Then based on specific thresholds of each geo-spatial factors, the area was classified "Forested" or "Deforested".

Once the area was classified accordingly, an impact analysis was conducted on factors such as: Crop, Local Climate, Soil. Finally, the parameters including Rate of Deforestation, Total Area Lost, Hotspot, Human activity causes and Infrastructure Development causes were visually represent in a Map.

Tools Used: QGIS , Juypter Notebook

Languages: Python, HTML,CSS,JavaScript

Data Sources: Google Earth Engine, Open Building, NASA Power Data Access Viewer, etc.


                                                                                     ARCHITECTURE DIAGRAM
![Image](https://github.com/user-attachments/assets/5f0fa00c-7309-469b-8de2-c76c73f7c6fc)
