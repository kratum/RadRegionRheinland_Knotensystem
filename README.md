# RadRegionRheinland_Knotensystem
Here is Point and Line Data for the RadRegionRheinland Knotenpunktsystem extracted from OSM and extended by elevation Data from SRTM.


## Overpass Query 
```
/*
This has been generated by the overpass-turbo wizard.
The original search was:
“ref=RRR”
*/
[out:json][timeout:25];
// gather results
(
  // query part for: “ref=RRR”
  node["ref"="RRR"](50.54, 6.2, 51.22, 7.777);
  way["ref"="RRR"](50.54, 6.2, 51.22, 7.777);
  relation["ref"="RRR"](50.54, 6.2, 51.22, 7.777);
);
// print results
out body;
>;
out skel qt;
```
