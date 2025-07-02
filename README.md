# Dam Suitability Analysis Project

This project uses Python and geospatial libraries to identify suitable locations for dam construction in Rajasthan, India.

### Workflow:
1.  Merge raw DEM and Landsat data.
2.  Calculate NDVI, Slope, and Distance to Rivers.
3.  Reclassify each factor into a suitability score.
4.  Combine all factors using a weighted overlay to produce a final suitability map.

