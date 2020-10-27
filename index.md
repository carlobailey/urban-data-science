## Urban Data Science & Analytics at CCNY

Resources for urban research that explore, architecture, urbanism, and authoritative forces that shape the built environment at CCNY CUNY.

------
<br/><br/>

### Learning Objectives
This site is intended to help students:
- Learn how to download, explore and visualize opensource urban data
- Gain fluency with mapping and other data visualization techniques
- Ask basic questions of data and how to interpret results

### Technology
Resources are focused around:
- Python & Jupyter Notebooks – for coding
- Pandas - for data analytics
- Geopandas – for spatial analytics
- Kepler GL - for mapping
- Tableau - for general data visaulization and analysis


### Computing Resources
Students are assumed to have access to a personal computer, ideally a laptop, to follow along with the below tutorials and in-class workshops. You will need to download and install both [Tableau](https://www.tableau.com/academic/students) and [Python](https://realpython.com/installing-python/) in order to complete tutorials (I recommend installing Python through the [Microsoft Store](https://realpython.com/installing-python/#how-to-install-from-the-microsoft-store) if using Windows and installing via [Homebrew](https://realpython.com/installing-python/#how-to-install-from-homebrew) if using a Mac). Once you have Python setup on your system, install [Jupyter Notebooks](https://jupyter.org/install) as we will be using it for a lot of the analytical work. Please contact the instructor directly with any issues or questions related to hardware/software.

During the semester, students are encouraged to scour the internet for other opensource resources on urban analytics. A couple of good ones:
- [Methods in Spatial Research](https://github.com/CenterForSpatialResearch/methods-in-spatial-research-sp2020), from GSAPP's Center for Spatial Research. A deep dive into using QGis.
- [Urban Data Science](https://github.com/gboeing/urban-data-science), from UC Berkley. For those interested in more advanced applications.

------
<br/><br/>

## Material

### [Tutorial-1: Downloading and mapping census data with Python](https://nbviewer.jupyter.org/github/carlobailey/urban-data-science/blob/gh-pages/tutorials/Mapping_Census_Data.ipynb)
This example goes through how to interact with the Census API to download data on US households across space and time. We will go through the steps of obtaining household income and educational attainment data and then use the Geopandas library to visualize the data in Brooklyn, NY.

### [Tutorial-2: Downloading and mapping property data with Tableau](tutorials/Mapping_data_tableau.md)
This tutorial shows how to download tax lot data from the NYC Planning department site, aggregate the average residential floor area per zipcode, and then create a choropleth map in Tableau.

### [Tutorial-3: Analyzing geospatial (parks) data with Python](https://nbviewer.jupyter.org/github/carlobailey/urban-data-science/blob/gh-pages/tutorials/analyzing_geospatial_data.ipynb)
This tutorial demonstrates how to work with geospatial data in python. Through exploring the relationship between a neighborhood's income level and total park area, you will learn how to utilize geopandas and the scipy libraries to aggregate and surface simple stats at the zip code level.

### [Tutorial-4: Analyzing geospatial (property value) data with Python](https://nbviewer.jupyter.org/github/carlobailey/urban-data-science/blob/master/tutorials/Analyzing_geospatial_data_poi.ipynb)
This tutorial extends some of the initial spatial analytics work we did in the previous tutorial by looking at more granular techniques to surface insights from geospatial data. Specifically, it demonstrates how to explore the relationship between NYC property values and proximity to cultural institutions.

### Tutorial-5: Analyzing data with Tableau
Coming soon...
This tutorial demonstrates how to analyze US obesity rates in relation to other socioeconomic indicators like commuting and food access patterns. We will explore data in the top 500 US metro areas and use Tableau to map and generate insights.

### Tutorial-6: Creating web-based (bivariate) 3D maps (Kepler GL + Python)
Coming soon...

### Tutorial-7: Analyzing the relationships between datasets (correlation)
Coming soon...

------
<br/><br/>

## Datasets

Below are a links to free and open datasets, sorted by subject area, that you may choose to use within your own research. This list is non-exhaustive and students are encouraged to seek out other sources if these do not align with your research agenda.

### Health
- [CDC data portal](https://ephtracking.cdc.gov/DataExplorer/#/): National Environmental Public Health Tracking Network

### Transportation
- [Bureau of Transportation Statistics](https://www.bts.gov/latch/latch-data)

### Points of Interest
- [SNAP Location](https://github.com/jshannon75/snap_retailers)

### Demographic
- [US CENSUS (ACS)](https://data.census.gov/cedsci/)
