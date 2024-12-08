---
title: "Remote Sensing"
collection: GIS-maps
excerpt: "Projects with geospatial data analysis and processing by using remote sensing technology."
---
### Project 1: Urban Surface Temperature Change Time Series Analysis

<img src="{{site.url}}/images/GIS-maps/Remote-sensing/timeseries.png" alt="Time series analysis">


This study investigates the impact of the COVID-19 epidemic on land surface temperature (LST) in Wuhan's central city.

Using MODIS LST data from 2013 to 2023 (resource from: [Google Earth Engine](https://earthengine.google.com/)), and applying the [BFAST algorithm](https://cran.r-project.org/web/packages/bfast/bfast.pdf) in [R](https://www.r-project.org/) for time series analysis, the study identifies significant breakpoints in LST during the 2020 urban lockdown, revealing reductions in urban surface temperature. These changes are attributed to decreased human activity and energy consumption, highlighting a temporary mitigation of the urban heat island effect.

### Project 2: Land Cover Classification with Random Forest

<img src="{{site.url}}/images/GIS-maps/Remote-sensing/ml-landcover.png" alt="machine learning" >

This project involves a **machine learning** algorithm for remote sensing: classifying satellite images into land cover types on a per-pixel basis over Zurich, Switzerland.

Using a [Python](https://www.python.org/) implementation of the Random Forest classifier, we will process Image 1 by extracting band features and calculate metrics to train the classification model for various land cover classes. The trained model will then predict land cover types in Image 2, demonstrating the application of supervised classification in remote sensing analysis.

### Project 3: Land Use Classification with AlexNet and ResNet

<img src="{{site.url}}/images/GIS-maps/Remote-sensing/dl-landuse.png"  alt="deep learning">



This project explores land-use classification using satellite images from the [UCM Dataset](https://paperswithcode.com/dataset/uc-merced-land-use-dataset), leveraging **deep learning** techniques in [Python](https://www.python.org/).

The study includes two tasks: (1) single-label classification, assigning a general category to each image, and (2) multi-label classification, identifying multiple features within each image to determine detailed land-use classes.

CNN models AlexNet and ResNet are employed to extract features and achieve high classification accuracy.
