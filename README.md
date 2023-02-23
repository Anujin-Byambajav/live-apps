# Live apps repo

This repository contains apps that can be visualized via GitHub pages.

### ArcGIS JS API APPS

This folder contains apps I created using [ ArcGIS Maps SDK for JavaScript](https://developers.arcgis.com/javascript/latest/).

The Mongolia population application shows the population of Mongolia between 1990 - 2013 by [soums](https://en.wikipedia.org/wiki/Districts_of_Mongolia). Population is visualized using the [DotDensityRenderer](https://developers.arcgis.com/javascript/latest/api-reference/esri-renderers-DotDensityRenderer.html). Once the application loads, users can display either total, male or female by different years. To do this, users can drag the slider thumb and the application will update the population layer renderer to display the population for the given year.

Users also can select to display total, male or female population data. This will update the layer's renderer and will also update the `Country population by years` chart to reflect the selection. The chart is created by running `sum` statistics query. The summary statictics query adds population of each soum by selected category (total, male or female). The query result is processed to display the chart.

![image](https://user-images.githubusercontent.com/106698838/213625666-243c4413-bbd8-44a8-bc01-61a7d17902e9.png)

[view the code](https://github.com/Anujin-Byambajav/live-apps/tree/main/arcgis-js-api-apps)

[view live sample](https://anujin-byambajav.github.io/live-apps/arcgis-js-api-apps/mongolia-population/index.html)
