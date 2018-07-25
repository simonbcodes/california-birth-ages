# California Birth Numbers by Age of Mother

This project gets it's data from the California Open Data Portal, located [here](https://data.ca.gov/dataset/births-age-mother-1960-current). The visualization is done using plotly as opposed to bokeh or matplotlib, as I wanted to test out the effectiveness of this library in comparison to the others.

The Jupyter notebook for this project, which contains the visualizations and explanation of the aspects of the project, can be found [here](https://nbviewer.jupyter.org/github/simonbcodes/california-birth-ages/blob/master/Birth%20Years.ipynb)

## Installation

To install this project on on your system, clone this repository. After this, run

```
pipenv install --dev
```

to install the various dependencies that this project requires. From here, you can open the Jupyter notebook by running

```
pipenv shell
jupyter notebook
```

This should start this project's virtual environment, and open the notebook in a browser window for you to mess with to your heart's desire.

## APIs/Dependencies (Also found in Pipfile)
- pandas
- plotly
- colorlover
- jupyter
