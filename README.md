# GAC_Segmentation
Semiconductor yield root cause finding is a challenging analysis, due to pattern uniqueness from root cause. For example, different defect site locations, cause by different root causes [Fig1,2].

 
 
 ![alt text](https://github.com/twming/GAC_Segmentation/blob/main/fig1.png?raw=true)

Fig. 1. Each localized pattern is different in size and location on the map.

 ![alt text](https://github.com/twming/GAC_Segmentation/blob/main/fig2.png?raw=true)
Fig. 2. Pattern site location and root cause.

The objectives of this analysis is to segment the defect from wafer and create the “fingerprint” to represent each type of defects. In these cases, we use the geodesic active contour (GAC). Furthermore, the fingerprint will be used to group the maps by site locations and (same) search the maps searching by cosine similarity method.
