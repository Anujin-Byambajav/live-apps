# Sample using ArcGIS Maps SDK for JavaScript
This repository contains a sample that uses the ArcGIS Maps SDK for Javascript version 4.25.

This sample uses the statistics query by defining the [outStatistics](https://developers.arcgis.com/javascript/latest/api-reference/esri-rest-support-Query.html#outStatistics) parameter and displays the results of the query in a chart. 

This application shows the Mongolian population range from 1990 to 2013. The population is queried by gender and years, and is displayed in a bar chart. Population is visualized using the [DotDensityRenderer](https://developers.arcgis.com/javascript/latest/api-reference/esri-renderers-DotDensityRenderer.html). Each dot represents 100 people. The population bar chart is updated as the user selects the option from dropdown menu while the dot density renderer is updated as the user drags or changes the slider widget. Slider widget allows the user to switch between different years and its population range.

![image](https://user-images.githubusercontent.com/106698838/213625666-243c4413-bbd8-44a8-bc01-61a7d17902e9.png)


[view the code](https://github.com/Anujin-Byambajav/arcgis-js-api-apps/tree/main/mongolia-population)

[view live sample](https://anujin-byambajav.github.io/arcgis-js-api-apps/mongolia-population/index.html)

### Feature Service
This application uses feature service to create a feature layer. 

[the URL](https://services.arcgis.com/ZsdWaRdt8de0J6c5/ArcGIS/rest/services/Population_density_Mongolia/FeatureServer/0) of the feature service.
