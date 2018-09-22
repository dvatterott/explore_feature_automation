# Exploring Feature Tools

In this jupyter notebook, I explore feature tools, which is a tool that automates feature engineering. I use the Online Retail dataset from the UCI repo (link below).

Here's the Feature tools blog [post](https://towardsdatascience.com/why-automated-feature-engineering-will-change-the-way-you-do-machine-learning-5c15bf188b96), which I followed here.

This notebook accompanies a presentation at Venture Cafe on 10/4. The presentation is available at my [website](www.danvatterott.com/presentation/).

Note that feature tools is computationally expensive, so I allow users to simple load data where I've already applied featuretools' automated feature engineering. 

This notebook is available on binder. Follow the link to access it there. Otherwise, use [enviornment.yml](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) to replicate my python environment used here. 

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dvatterott/explore_feature_automation/master)

Here's a standard [link](https://mybinder.org/v2/gh/dvatterott/explore_feature_automation/master) to the binder notebook.

## Quick notes:
How to export environment- conda env export --no-builds > environment.yml

How to download the data:
* curl https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx > OnlineRetail.xlsx

