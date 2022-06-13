# test-dash-app

This repo includes files to run the sample dash app described in the Domino [Get Started with Dash](https://docs.dominodatalab.com/en/latest/user_guide/de2589/get-started-with-dash) documentation.

It includes two files:
1. [`app.py`](app.py) -- This is taken verbatim from the tutorial.
2. [`app.sh`](app.sh) -- This is modified to set up a python [venv](https://docs.python.org/3/library/venv.html#), install the required dash packages, and run the [`app.py`](app.py) script using the venv python.  This removes the need to create a custom environment to install [Dash](https://plotly.com/dash/).
