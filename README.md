# Water Risk Classification
*Leonardo Harth* & *John Michael LaSalle*



An attempt to classify global water risk typologies. Final project for [CPLN 691 Geospatial Data Science in Python](https://github.com/MUSA-620-fall-2019).

# Setup
Create the `water-risk-classification` virtual environment with `conda env create -f environment.yml`
Update the environment with `conda env update --name wrc --file environment.yml --prune`

# Git Usage

1. Download updates with `git pull`
2. Make changes to files.
3. Stage changes with `git add .`
4. Create commit with `git commit -m "commit message"`
5. Push commit with `git push`

If you get an error like `error: Pulling is not possible because you have unmerged files.` use `git reset --hard origin/master` to overwrite your local version. Save any updated code outside of the `water-risk-classification` folder.

# Data Sources
1. [WRI Aqueduct](https://www.wri.org/aqueduct/data)
2. [Global Human Settlements Layer](https://ghsl.jrc.ec.europa.eu/data.php)
3. [SEDAC Infant Mortality](https://sedac.ciesin.columbia.edu/data/set/povmap-global-subnational-infant-mortality-rates-v2/data-download)
4. [Version 4 DMSP-OLS Nighttime Lights Time Series](https://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html)
