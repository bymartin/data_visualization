# data_visualization

Project from the book Python Crash Course 2nd edition by Eric Matthes

Requires X11 
Run xming in windows 
then > export DISPLAY=:0

Install Matplotlib if necessary:
Example visualizations: https://matplotlib.org/stable/gallery/index.html
> python3 -m pip install --user matplotlib
>

Install Plotly
Gallery of chart types at https://plot.ly/python/
Plotly User Guide in Python at https://plot.ly/python/userguide/
The python figure reference at https://plot.ly/python/reference/
shows all the settings to configure Plotly visualizations.
> python3 -m pip install --user plotly

Install Requests
> python3 -m pip install --user requests


When trying to use Matplotlib for the first time, I got this error:
mpl_squares.py:7: UserWarning: Matplotlib is currently using agg, which is a non-GUI backend, so cannot show the figure.
  plt.show()
  
This was resolved by installing tkinter in my WSL Ubuntu environment:
> sudo apt-get install python3-tk
> 

The weather data from the project came from NOAA (csv format):
https://ncdc.noaa.gov/cdo-web/.

Earthquake data (json):
https://earthquake.usgs.gov/earthquakes/feed/
https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

World Fires:
https://earthdata.nasa.gov/earthobservation-data/near-real-time/firms/active-fire-data/

data directory:
input files for the programs

GitHub API documentation at https://developer.github.com/v3/

Hacker News http://news.ycombinator.com/


