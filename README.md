# Water Risk Classification
*Leonardo Harth* & *John Michael LaSalle*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jmlasalle/water-risk-classification/master?filepath=app.ipynb)

[![badge](https://img.shields.io/badge/Launch-App-F5A252.svg?logo=data:image/png;base64,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)](https://mybinder.org/v2/gh/jmlasalle/water-risk-classification/master?filepath=%2Fpanel%2Fapp)

# Introduction
Our project uses the [Aqueduct Alliance Global Maps 3.0](https://www.wri.org/resources/data-sets/aqueduct-global-maps-30-data) data as the initial data source. This dataset aggregates diverse indicators of Water Risk for every water basin in the world. The information it conveys informs us about issues such as water depletion, water quality, and extreme conditions – like drought and flood. The richness of this data piked our curiosity, leading us to wonder what other factors are associated with these characteristics. Is low water quality more prevalent in developing countries? Is it correlated to the human development index of its surroundings? We embraced this challenge as a means to explore these relationships.

We have chosen to use the [Global Human Settlement Layer](https://ghsl.jrc.ec.europa.eu/data.php) from the European Commission as a measure of population density, the [global subnational infant mortality rates dataset](https://sedac.ciesin.columbia.edu/data/sets/browse?facets=theme:poverty) from the Socioeconomic Data and Applications Center (SEDAC) as a proxy for the Human Development Index (IDH), and the [Nighttime Lights Annual Composites](https://data.noaa.gov/metaview/page?xml=NOAA/NESDIS/NGDC/STP/DMSP/iso/xml/4393.xml&view=getDataView&header=none) from the National Oceanic and Atmospheric Administration (NOAA) as a proxy for economic development – as [recent research](https://www.aeaweb.org/articles?id=10.1257/aer.102.2.994) indicates that night light can be used to measure income growth.

Our main dataset is comprised of vector data. Each basin is a multipolygon, that has diverse features. Each feature is presented in its raw value, a 0 to 5 score, a label (categorical string), and a categorical integer. We chose to work solely with raw values. The full description of the categories can be found [here](https://github.com/wri/aqueduct30_data_download/blob/master/metadata.md). All of our complimentary datasets are raster images.

# Methods – Data Wrangling and Modeling
The first step we had to take was to combine these 4 datasets into one. We used our water dataset as the baseline. Since it is a vector data (and all other datasets are rasters), we aggregated the mean values of the pixels that fall within the boundaries of each basin using the zonal statistics tool of the `rasterstats` library. This allowed us to have a single dataset, in which each row represents a basin, having all the original raw water risk values, plus the mean values of child mortality, night light, and population density.

Unfortunately, several lines of this dataset have NA values. We have tried to use the [multivariate feature imputation tool](https://scikit-learn.org/stable/modules/impute.html) from the Scikit-learn library to fill those values, but the results did not look good. Since it is advertised by the developer that this tool is experimental, we chose to remove the NA values from our dataset instead of imputing values to them, thus reducing the number of rows from 68,506 to 42,823.

The combined dataset has 11 water risk features and 3 aggregated features (mean child mortality, mean populational density, and mean night light). Before we performed the cluster analysis, we have subset the water risk features into 3 groups:

*  __Physical Risk variables__: this group comprises variables related to the quality of the water and water systems infrastructure – Untreated connected wastewater (ucw_raw), Unimproved/no drinking water (udw_raw), and Unimproved/no sanitation (usa_raw).
*  __Water depletion variables__: This group holds variables regarding the scarcity or future scarcity of water – Baseline water stress (bws_raw), Baseline water depletion (bwd_raw), Interannual variability (iav_raw), Seasonal variability (sev_raw), and Groundwater table decline (gtd_raw).
*  __Extreme conditions variables__: This group has variables related to flood and drought – Riverine flood risk (rfr_raw), Coastal flood risk (cfr_raw), and Drought risk (drr_raw).

We have used the standard scaler in a copy of our dataset to run the Kmeans clustering algorithm. To determine the optimal number of clusters in our Kmeans analysis, we used a for loop that ran the algorithm in a range from 1 to 20 clusters, appending the inertia (the sum of the squared distances to clusters) values for each number of clusters. We plotted then the “elbow function” for each of our variable groups, to determine the optimal number of clusters (the optimal value should significantly reduce the inertia in relation to its previous value, whereas the subsequent value improves it only marginally). We have used then 10 clusters for every group of variables. This allowed us to specify to which cluster each observation in the dataset belongs.

We have learned that Kmeans cluster analysis is not an optimal tool to handle this kind of data. However, we hypothesized that the clusters generated by the Kmeans analysis could be used as an input in a DBScan cluster analysis.

To perform the DBScan cluster analysis, the first step we took was to convert the multipolygons into points. We did that by converting the geometry of the observations in the dataset into the centroids of these shapes. We have also converted the dataset into the 6933 EPSG, to get units in meters. Since we wanted the labels from the Kmeans analysis (which were added to the untransformed dataset), we used the standardscaler tool again, transforming the raw variables, the x and y coordinates, and the Kmeans labels. We used this dataset as an input in the DBScan cluster analysis.
The visualization web app

# Conclusions and final remarks

# User Notes

An attempt to classify global water risk typologies. Final project for [CPLN 691 Geospatial Data Science in Python](https://github.com/MUSA-620-fall-2019).

## Setup
Create the `water-risk-classification` virtual environment with `conda env create -f environment.yml`
Update the environment with `conda env update --name wrc --file environment.yml --prune`

## Git Usage

1. Download updates with `git pull`
2. Make changes to files.
3. Stage changes with `git add .`
4. Create commit with `git commit -m "commit message"`
5. Push commit with `git push`

If you get an error like `error: Pulling is not possible because you have unmerged files.` use `git reset --hard origin/master` to overwrite your local version. Save any updated code outside of the `water-risk-classification` folder.

## Data Sources
1. [WRI Aqueduct](https://www.wri.org/aqueduct/data)
2. [Global Human Settlements Layer](https://ghsl.jrc.ec.europa.eu/data.php)
3. [SEDAC Infant Mortality](https://sedac.ciesin.columbia.edu/data/set/povmap-global-subnational-infant-mortality-rates-v2/data-download)
4. [Version 4 DMSP-OLS Nighttime Lights Time Series](https://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html)
