# data_viz_python
This Jupyter Notebook contains different examples of charts for visualizing data using matplotlib in Python.

## Matplotlib 
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

The charts that were made:

### -> matplotlib.pyplot.bar
matplotlib.pyplot.bar(x, height, width=0.8, bottom=None, *, align='center', data=None, **kwargs)
Make a bar plot.

The bars are positioned at x with the given alignment. Their dimensions are given by height and width. The vertical baseline is bottom (default 0).

Many parameters can take either a single value applying to all bars or a sequence of values, one for each bar.

### -> matplotlib.pyplot.pie
matplotlib.pyplot.pie(x, explode=None, labels=None, colors=None, autopct=None, pctdistance=0.6, shadow=False, labeldistance=1.1, startangle=0, radius=1, counterclock=True, wedgeprops=None, textprops=None, center=(0, 0), frame=False, rotatelabels=False, *, normalize=True, hatch=None, data=None)
Plot a pie chart.

Make a pie chart of array x. The fractional area of each wedge is given by x/sum(x).

The wedges are plotted counterclockwise, by default starting from the x-axis.

### -> matplotlib.pyplot.stackplot
matplotlib.pyplot.stackplot(x, *args, labels=(), colors=None, baseline='zero', data=None, **kwargs)
Draw a stacked area plot.

### -> matplotlib.pyplot.plot
matplotlib.pyplot.plot(*args, scalex=True, scaley=True, data=None, **kwargs)
Plot y versus x as lines and/or markers.

### -> matplotlib.pyplot.hist
matplotlib.pyplot.hist(x, bins=None, range=None, density=False, weights=None, cumulative=False, bottom=None, histtype='bar', align='mid', orientation='vertical', rwidth=None, log=False, color=None, label=None, stacked=False, *, data=None, **kwargs)
Compute and plot a histogram.

### -> matplotlib.pyplot.scatter
matplotlib.pyplot.scatter(x, y, s=None, c=None, marker=None, cmap=None, norm=None, vmin=None, vmax=None, alpha=None, linewidths=None, *, edgecolors=None, plotnonfinite=False, data=None, **kwargs)
A scatter plot of y vs. x with varying marker size and/or color.

### -> matplotlib.pyplot.subplot
matplotlib.pyplot.subplot(*args, **kwargs)
Add an Axes to the current figure or retrieve an existing Axes.

#### Source: Matplotlib documentation
https://matplotlib.org/stable/api/pyplot_summary.html

