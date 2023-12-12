# Documentation

It is the GitHub repo for the Udemy course: [Geospatial data analysis with python](https://www.udemy.com/course/geospatial-data-analysis-with-python/?referralCode=5B58238C5392672D17B7)

## Course Outline

### 1. Vector data analysis with geopandas and shaply
Geopandas, built on Python, is a powerful library for working with geospatial data. It leverages the capabilities of Pandas for data manipulation and couples it with tools from Shapely and other libraries to handle geometric objects. Geopandas enables efficient handling of geospatial datasets, allowing users to read, write, analyze, and visualize various spatial formats like shapefiles, GeoJSON, and more. It offers functionalities such as spatial joins, overlays, geometric operations, and map plotting, making it a go-to choice for tasks involving geographic data analysis, manipulation, and visualization within a familiar Pandas framework.

![geopandas demo output](https://github.com/iamtekson/geospatial-data-analysis-python/blob/master/image/geopandas_output.png)

### 2. Raster data analysis with Rasterio
Rasterio is an essential Python library tailored for raster data analysis, offering a robust suite of tools for working with geospatial raster datasets. Leveraging the power of GDAL (Geospatial Data Abstraction Library), Rasterio facilitates the reading, writing, and processing of diverse raster formats such as satellite imagery, digital elevation models, and aerial photographs. Its functionalities enable users to efficiently access, manipulate, and extract information from raster data, perform complex geospatial operations, and seamlessly integrate with other Python libraries for advanced analysis and visualization, making it a pivotal tool for raster data exploration and analysis within the Python ecosystem.

![rasterio demo output](https://github.com/iamtekson/geospatial-data-analysis-python/blob/master/image/lulc_class_dn_values.png)

### 3. Beautiful map layout using geopandas
Geopandas provides a versatile framework for creating visually stunning and informative map layouts. By leveraging its integration with Matplotlib, Geopandas allows users to craft visually appealing maps with ease. With functionalities for plotting spatial data directly from GeoDataFrames, users can customize map elements, such as colors, legends, labels, and symbology, to effectively communicate spatial information. Additionally, Geopandas' compatibility with other visualization libraries like Seaborn and Plotly extends the possibilities for creating interactive and polished map visualizations. Whether for professional presentations, data exploration, or publication-ready visualizations, Geopandas empowers users to craft beautiful and informative map layouts that effectively convey complex spatial insights.

![geopandas map layout](https://github.com/iamtekson/geospatial-data-analysis-python/blob/master/image/gpd_map_output.jpg)

### 4. Working with large datasets using Dask
Dask is a versatile parallel computing library in Python designed to handle large datasets that do not fit into memory. It provides efficient tools for distributed computing and task scheduling, allowing users to process data that exceeds the memory capacity of a single machine. With Dask, users can perform computations in parallel across multiple cores or even on clusters, utilizing its array, data frame, and bag collections to manage and manipulate large datasets seamlessly. Its ability to scale to larger-than-memory datasets makes it an ideal choice for tasks involving big data analytics, machine learning, and other computationally intensive operations where traditional tools might struggle. By harnessing Dask's capabilities, users can efficiently tackle large-scale data processing and analysis while optimizing computational resources.

### 5. Generate raster statistics using raster stats
The `rasterstats` library in Python is a powerful tool for generating statistics from raster datasets based on vector geometries. Leveraging the capabilities of `rasterio` and `fiona`, `rasterstats` allows users to extract statistics, such as mean, sum, count, or custom calculations, from a raster dataset (like satellite imagery or elevation data) based on the geometries defined in vector data (such as polygons or points). By overlaying vector geometries on the raster, it computes summary statistics for each geometry, providing valuable insights into the characteristics of the underlying raster data within those specific regions or features. This library facilitates efficient analysis, making it useful for tasks like land cover analysis, environmental studies, and various geospatial analyses by aggregating raster information according to defined vector regions.

![rasterstats demo image](https://github.com/iamtekson/geospatial-data-analysis-python/blob/master/image/zones_elevation.png)

