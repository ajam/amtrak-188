Amtrak 188
===

Data related to our coverage of Amtrak 188's derailment on May 12, 2015. Related story and graphics: <http://america.aljazeera.com/multimedia/2015/5/map-derailed-amtrak-sped-through-northeast-corridor.html>

From that page:

> Al Jazeera obtained the data by periodically downloading train locations from Amtrak's online "Track a Train" [interactive map](http://www.amtrak.com/train-routes), which displays the locations and speeds of Amtrak trains across the country. For this graphic, data is limited to northbound trains on the Northeast Regional line traveling through the site of Tuesday's crash.

It currently contains three files:

* `curve-bounding-box.gejson` — The bounding box we used to designate the 50 mph curve where 188 derailed.
* `unique-trains-in-bounding-03-05-flat-northbound.csv` — All northbound "Northeast Regional" trains as a flat csv between March 1 and March 12, 2015 for which we obtained a speed reading inside the above bounding box.
* `unique-trains-in-bounding-03-05-northbound.geojson` — All northbound "Northeast Regional" trains as GeoJson between March 1 and March 12, 2015 for which we obtained a speed reading inside the above bounding box.
