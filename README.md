# Zipcode Choropleth with Jupyter Notebook, Plotly, Pandas and Mapbox
## Synopsis
In this tutorial, we will be creating a choropleth of San Diego's Zipcodes based on Zillow's Price-to-Rent Ratio.  
## Overview
* To get started, you'll need Jupyter Notebook with Python 2.X - this code won't work out-of-the-box with Python 3.X.  I prefer installing Anaconda since it allows you to launch Jupyter Notebook from Anaconda Navigator, and allows you to install both Python 2.X and 3.X and switch between then easily as an Environment in Anaconda Navigator.  
* Next you'll need to clone this repository to your machine with a Git client
* Then you may need to check that all those "import" statements are libraries you already have installed, if not, Anaconda Navigator can easily help you to search and install them.  You'll likely need to restart the Jupyter Notebook kernel to see the new libs.
* Finally, you'll need to enter your Mapbox token in the Jupyter Notebook, see below...
## Mapbox Access Token
To plot on Mapbox maps with Plotly you'll need a Mapbox account and a [Mapbox Access Token](https://www.mapbox.com/studio) which you can add to your [Plotly settings](https://plot.ly/settings/mapbox). If you're using a Chart Studio Enterprise server, please see additional instructions here: https://help.plot.ly/mapbox-atlas/. 
