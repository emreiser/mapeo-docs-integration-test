# Importing and using external geospatial data

When creating data in **Territory** mode, you may want to incorporate or utilize geospatial data from a source outside of ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop **Territory** Mode.

One key source of data that you may want to access in ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop **Territory** mode is data that was collected via  ![](https://lh4.googleusercontent.com/h29dCuHGSwyXA6NBPzGBOWNjMXb3T7eSFam0RnCTtp1Aui8uQgtioJnREuOkPJ9idCfxOHcjkBUBNvIRRvbCA\_zW1sigl\_fn3EFoSq4pomrkehyYg6hPLkcr1nabg-FNR2y9YP\_-) Mapeo Mobile, synchronized with your ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop device, and available in ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop **Observations** mode.

Additional data sources to use could be any of the following:

* `.GeoJSON` (a commonly used format by many GIS tools such as QGIS or Mapbox, and also available as an export option in both ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop **Territory** and **Observations** modes)&#x20;
* `.kml` / `.kmz` (A file extension used by Google Earth Pro and related tools, but commonly used by many applications)&#x20;
* Shapefile (`.shp` and several other files, created by Esri for use in their ArcGIS software but commonly used by many applications)
* `.gpx` (a GPS data file that contains waypoints, routes, and tracks; generated by handheld GPS devices by Garmin and others)&#x20;

There are currently three different ways to work with the above kinds of external data.&#x20;

## Importing `.GeoJSON` or shapefile data as territory data&#x20;

You can import a file containing geospatial data (in `.GeoJSON` and shapefile formats) directly into your ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop **Territory** mode database. This will add all of the data (points, lines, and areas) to your ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop territory data set as uncategorized features. You can then edit the features in the same way as any features that were created directly in **Territory** mode.

* In the **Top menu** bar, click on **File** and then select **Import territory data**.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-01.jpg)

* In the file browser pop-up window, navigate to the directory where the file you want to import is located. Select the file you wish to import (in either `.GeoJSON` or shapefile format).&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-02.jpg)

* Currently, Mapeo does not provide any messaging once you have done so, but if the file you have selected has geospatial data that can be imported, Mapeo will begin importing the data. ![](https://lh5.googleusercontent.com/eVaw28jOyvIaFA5qBZlIXKQ5xKIlqlt32kPTs818ynoMkT1CYyYe4EZokBrb3bNcQP0fFJYdUnzXRslKcKyxwJT-EsRqOX0qqj5sI3AxC7jw1O0yQhBLIYcwDm2ZblG8Wr1TxPYQ) You may see a processing icon at the bottom right of the map, indicating that data is being imported.&#x20;
* Upon successful import, the data will not show up right away; you may have to reload Mapeo by pressing **CTRL-R** or restarting.
* Once imported and refreshed, the data will appear as uncategorized features on your map. Remember that you will need to be zoomed in to the area where they are located in order to see them on the background map.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-03.jpg)

* You can then edit the features in the same way as any features that were created directly in **Territory** mode.

![](../../../.gitbook/assets/Md-territory\_importing-04.jpg)

{% hint style="info" %}
**Note**: to import a shapefile, ![](https://lh5.googleusercontent.com/bdNxQRS9mSJlaKfeYAUuqnhwjnkpXLYxjXEraIF2Y6JG7eyWI\_grgr8HJ5PKGER8wB3xIgmLse9XuLQKxRlcLrYc1ZV8fzB6GwNRV22uGoWWcQ2dtQs2RKh1XN\_v8PocFOMU24L6) Mapeo Desktop is configured to look for `.shp` file. However, a shapefile consists of a number of additional files with other extensions including `.shx`, `.dbf`, `.sbn` and several additional optional files. Make sure these files are in the same directory as your `.shp` file or the import will fail.
{% endhint %}

{% hint style="info" %}
**Note**: currently, it is not possible to import `.kml` / `.kmz` or `.gpx` data directly into your **Territory** database. See the next section for more information on how to use these as a map data overlay.&#x20;
{% endhint %}

## Using geospatial data as a temporary custom map data overlay&#x20;

You can add geospatial data as a temporary data layer that is displayed on top of your background, as a reference for creating **Territory** data but without including this data directly into your database. This could be useful if you have some geospatial data that you want to display for reference when creating data, such as place names, rivers and creeks, roads and paths, or zonal data. In **Territory** mode, this is currently known as **custom map data**.

There are four types of data that can be added as **custom map data**: `.gpx`, `.kml`, `.geojson` and `.json`.

There are two ways to add custom map data to **Territory** mode:

(1) Using the ![](https://lh6.googleusercontent.com/iF7rEqSXh\_KG5b\_PIQHVn\_h7r72lgrqaXUlyPbFE\_D4xV86Q3DU\_GVyLOepyi3G1QElmhH55NBw2S9Su6Tc7-n7LMhvW2hqsAp-PLP3j1c6v1133BsFqJPR8vyWtg\_ugdphxPN8p) **Map Data** window&#x20;

* Click on ![](https://lh6.googleusercontent.com/iF7rEqSXh\_KG5b\_PIQHVn\_h7r72lgrqaXUlyPbFE\_D4xV86Q3DU\_GVyLOepyi3G1QElmhH55NBw2S9Su6Tc7-n7LMhvW2hqsAp-PLP3j1c6v1133BsFqJPR8vyWtg\_ugdphxPN8p) **Map Data** <mark style="color:purple;">\[or use the</mark> <mark style="color:purple;"></mark><mark style="color:purple;">`F`</mark> <mark style="color:purple;"></mark><mark style="color:purple;">key shortcut on your keyboard]</mark>.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-05.jpg)

* Click on the **\[…] Edit custom data** layer button next to **Custom Map Data**. This button will be grayed out if no custom map data has been added.&#x20;
* From here, you can click the **Choose File** button to select a file, or add a data file URL if it is hosted on a server.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-06.jpg)

* If you are adding a file, in the file browser pop-up window, navigate to the directory where the file you want to import is located. Select the file you wish to import.

![](../../../.gitbook/assets/Md-territory\_importing-07.jpg)

* Click **Ok**. Now, you should be able to check the **Custom Map Data** option to show or hide the geospatial data that you’ve added.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-08.jpg)

(2) You also can drag the files from a file explorer window directly onto the map view. This will automatically add the file to the **Custom Map Data** option in the ![](https://lh6.googleusercontent.com/iF7rEqSXh\_KG5b\_PIQHVn\_h7r72lgrqaXUlyPbFE\_D4xV86Q3DU\_GVyLOepyi3G1QElmhH55NBw2S9Su6Tc7-n7LMhvW2hqsAp-PLP3j1c6v1133BsFqJPR8vyWtg\_ugdphxPN8p) **Map Data** panel.

On the **Territory** mode map, custom map data is shown with a pink outline and fill. If you hover over or click over any custom map data shapes, you will see attributes of the data in the **Edit feature** panel.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-09.jpg)

However, neither the attributes nor the geometries of custom map data can be edited, as this data is only made available as a visual reference for creating territory data. If you want to include this data directly into your territory database, then you need to import the data as described in [#importing-.geojson-or-shapefile-data-as-territory-data](importing-external-territory-information.md#importing-.geojson-or-shapefile-data-as-territory-data "mention")(and if your data is not in either of those formats, you may need to convert it using another software such as QGIS, ArcGIS, or web-based conversion tools such as [toGeoJSON](https://mapbox.github.io/togeojson/)).&#x20;

If you are unable to convert the file, then you can create new features by tracing over these overlain points, lines and areas. If you choose this route, you should make sure you are very zoomed in when you trace features to ensure you are as accurate as possible.&#x20;

![](../../../.gitbook/assets/Md-territory\_importing-11.jpg)

## About observation data in Territory mode&#x20;

While there is a different workflow for working with observation data in Mapeo that is documented in the [using-mapeo-desktop-to-manage-mapeo-mobile-data](../using-mapeo-desktop-to-manage-mapeo-mobile-data/ "mention") section, you can access Mapeo observation data in the **Territory** mode as well. Currently, Mapeo observation data will be displayed in the same style as Territory data.

It is also possible to edit Mapeo observations data in **Territory** mode, to a limited degree: you can edit feature details, and these changes will be reflected in **Observation** mode, and will also be synchronized with other Mapeo devices. However, if you move the location of a feature, or delete a feature in **Territory** mode, these changes will not be reflected in **Observation** mode; and, when you close and open **Territory** mode again, moved features will reappear in their original location as they were in **Observation** mode, and deleted features will reappear on the map.
