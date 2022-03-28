# Landslide_intensity
The geographic prediction of landslide occurrence is undertaken by assessing whether a slope may be stable or unstable. 
In other words, current practices treat slopes where a single landslide occurred in the same way as slopes where many landslides occurred. 
At the slope scale, this procedure inevitably underestimates the effect of multiple landslides. Here we model the number of landslides per slope instead. 
Then, thanks to the close relation that the number of failures shows with respect to landslide size, we convert the estimated number of landslides into 
estimated landslide areas. Ultimately, we also estimate the expected proportion of a slope affected by landslides. This framework is more informative than 
the stable/unstable paradigm and may help landslide risk mitigation strategies.

5_Terre_c2_20m.txt is the .txt file in which are added al the covariates;
Code_analysis represents the R code used for the model implementation;
LandslideArea@PXLevel.txt presents the landslise area at pixel scale;
PostProcess@SUlevel.txt lists the landslide and slope units peculiarites;
SU_Monterosso_Vernazza_c2.shp constitutes the shapefile of the slope units of the examined area.
