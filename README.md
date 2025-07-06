# 🌏📗 GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-3 🗾
# 🇮🇳 QGIS India's Geospatial Data Project

# 🌍 Project Overview
In Week 3 of this project, we zoomed into the West Zone of India, specifically targeting the states of Gujarat and Maharashtra. The aim was to perform a detailed sub-regional analysis, down to the district level, and integrate advanced terrain data using open-source GIS tools.
This step prepares the foundation for resource mapping using drone imagery and machine learning algorithms in later stages.
![A-3-3](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-3/blob/3772469c1f05678a83b99644f667a6006e0065d7/Screenshots/A-3-3.png)

# 🔍 Objective
- To focus on zonal-level resource mapping.
- To extract and visualize district-level data from Gujarat and Maharashtra.
- To integrate high-resolution elevation data using Mapzen Global Terrain.
- To prepare the terrain data for use in drone analysis and ML classification.

# ✨ Key Features
- Focused spatial analysis of Gujarat & Maharashtra within India’s West Zone.
- District-wise data extraction and mapping.
- Integration of Mapzen Global Terrain layer for elevation details.
- High-resolution terrain visualization.
- Use of composite elevation tiles from open sources.
- Ready-to-use layers for further machine learning integration.

# 🎯 Objective
- To narrow the focus of the resource mapping project to India’s West Zone for more region-specific analysis.
- To select and analyze the states of Gujarat and Maharashtra based on their geographical and resource diversity.
- To identify and visualize sub-regional administrative units (districts) within the selected states for detailed mapping.
- To integrate elevation data using the Mapzen Global Terrain plugin for enhancing topographical understanding.
- To lay the groundwork for integrating drone data and machine learning models in future phases of the project.

# 🛠️ Project Steps
1. Imported the base map and India shapefile into QGIS.
2. Selected the West Zone and isolated Gujarat and Maharashtra using attribute filtering.
3. Extracted district boundaries from respective state shapefiles.
4. Integrated Mapzen Global Terrain plugin:
    - Used it to load composite elevation tiles.
    - Aligned and overlayed the elevation data on selected states.
5. Saved the project layers for upcoming classification and drone imagery overlay.

# 🖥️ Screenshot
- (Here we are selecting the ACZ -> Districts ✅ -> States ✅)
    -![A-3-1](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-3/blob/3772469c1f05678a83b99644f667a6006e0065d7/Screenshots/A-3-1.jpg)
- (Here we are selectiing the Pervious data ACZ, Distrct & State aditionally we are addding the ext-data(West Zone))
    -![A-3-2](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-3/blob/3772469c1f05678a83b99644f667a6006e0065d7/Screenshots/A-3-2.jpg.jpeg)
- (Here we are selectiing the Pervious data ACZ, Distrct, ext-data(West Zone) aditionally we are enabeling the Mapzen Globaal Terrain -> enables to determine elivation points on the basis of height of the terain)
    -[A-3-3](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-3/blob/3772469c1f05678a83b99644f667a6006e0065d7/Screenshots/A-3-3.png)

# 📝 Requirements
- ⬇️ Install QGIS: [official website](https://qgis.org/download/) (latest version).
 1.	Clone this repository to your local machine: 
   2.	Open QGIS, and load the states.shp and districts.shp file located in the Main (Source Data File) folder.
   3.	Explore the data:
        - View district boundaries on the map.
        - Use QGIS query tools to view district codes and states.
        - Utilize QGIS analysis tools to study district borders and how they share boundaries with neighboring districts or states.

# ✅ Benefits of This Analysis
- Enables targeted regional mapping by breaking down zones into smaller administrative units.
- Elevation data supports terrain-sensitive planning, such as for agriculture, watershed, or infrastructure deployment.
- Foundation for ML-based resource classification, where elevation data can be a key feature.
- Valuable for planning drone survey routes based on terrain complexity.
- Promotes use of open-source tools and data for large-scale geospatial analysis.

# 👨‍💼Author
Mr. Rahul Bhuiya | 4th year CSE-AIML student at MCKVIE'26🎓

     
  

