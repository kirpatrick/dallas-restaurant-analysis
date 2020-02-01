# Dallas Restaurant Food Inspection Ratings
### SMU Data Science Bootcamp:  Project 1
Do restaurants with low health inspection scores tend to receive lower customer ratings in Yelp and Google?

### Team Members
Austin Potts, Kirpatrick Dorsey, Sean Kendrick Del Alcazar, Shane Gatenby, Stephanie Smith

## Hypothesis
If a Dallas restaurant has a poor health inspection score  (<70), that restaurant will also have a low customer rating on Google or Yelp.

| Inspection Score  | Interpretation    |
| ------------------|:-----------------:|
| >90               | Good              |
| 86-90             | Adequate          |
| 71-85             | Needs improvement |
| <= 70             | poor              |

## Null-Hypothesis
If a Dallas restaurant has a poor health inspection (<70) score in 2019, that restaurant will not have a low customer rating on Google or Yelp.

## Solution
1. Acquire the following API Keys:
    - [Google](https://developers.google.com/places/web-service/intro)
    - [Yelp Fusion](https://www.yelp.com/developers/documentation/v3)
2. Install 'Tech Stack' dependencies.
3. Clone this repository to your machine.
4. Unzip [Restaurant_and_Food_Establishment_Inspections__October_2016_to_Present_.xlsx](https://github.com/kirpatrick/dallas-restaurant-analysis/blob/master/resources/Restaurant_and_Food_Establishment_Inspections__October_2016_to_Present_.zip) and save in the resources folder.
5. Open [dallas_restaurant_analysis.ipynb](https://github.com/kirpatrick/dallas-restaurant-analysis/blob/master/dallas_restaurant_analysis.ipynb) using Jupyter Notebook.
6. Run each cell in the Jupyter Notebook starting at the top.

<b>NOTE:</b>  Some dependencies provide the option to (1) Limit data query calls (helpful when making numerous calls to Google and Yelp), (2) to load resources from outside the code, or to (3) load data from a previously generated data frame to continue execution.  Look for these options when you see *'Transition data to use...'*.


## Sources
- [Dallas Open Data](https://www.dallasopendata.com/browse?category=City+Services&provenance=official)
- [Google Places API](https://developers.google.com/places/web-service/intro)
- [Yelp Fusion API](https://www.yelp.com/developers/documentation/v3)

## Tech Stack
- [FuzzyWuzzy 0.17.0](https://www.geeksforgeeks.org/fuzzywuzzy-python-library/)
- [Git 2.17.1](https://git-scm.com/downloads)
- [Gmaps 0.9.0](https://jupyter-gmaps.readthedocs.io/en/latest/)
- [Matplotlib 3.1.1](https://matplotlib.org/)
- [Numpy 1.16.15](https://numpy.org/)
- [Pandas 0.25.1](https://pandas.pydata.org/)
- [Plotly 4.5.0](https://plot.ly/)
- [Python 3.7.4](https://www.anaconda.com/distribution/)
- [Scipy 1.3.1](https://www.scipy.org/)
- [Seaborn 0.9.0](https://seaborn.pydata.org/introduction.html)
