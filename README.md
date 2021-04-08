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
> python3 -m pip install --user plotly


When trying to use Matplotlib for the first time, I got this error:
mpl_squares.py:7: UserWarning: Matplotlib is currently using agg, which is a non-GUI backend, so cannot show the figure.
  plt.show()
  
This was resolved by installing tkinter in my WSL Ubuntu environment:
> sudo apt-get install python3-tk
> 


