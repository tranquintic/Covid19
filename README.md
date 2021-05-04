# Prerequisite
## Python 3
## Jupyter Notebook
Installation details can be found at: https://jupyter.org/install

# Local setup
## Clone project from git repo:
git clone https://github.com/tranquintic/Covid19.git

## Run jupyter notebook
jupyter notebook

## Open notebook name 'covid19CookCounty.ipynb'

## Sanity checked the output
Approach 1- Checking number of rows
If the number of days is the same as the number of rows in the output csv file, we should have enough information

Approach 2- Visualization
We can plot the cumulative cases and deaths of Cook county in Illinois. If the plots of the cumulative cases and deaths show only increasing values over time and have faster rates matching the timing of Covid waves in Illinois, it means we have the right output.

## Further Analysis
New cases and new deaths per day are calculated and plotted within time. It shows in both May and November that Illinos had the Covid waves. Since the population of Cook county takes up half of the population of Illinois, the experience with Covid in Cook county is similar to the experience that Illinois has overall. Cook county takes up approximately 40% of the total cases and total deaths in Illinois. Also, the ratios of deaths/cases of the wave in May is higher than the ratios for the November wave. This behavior indicates that the handling of the disease improved with time. Even though there are more new cases in November, the response was more effective in terms of treatment.

The dataset is interesing to visualize and analyze. However, for better predictive models, external information such as population and policy changes are needed. 

