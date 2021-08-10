# Data Visualization

matplotlib is probably the single most used Python package for 2D-graphics. It provides both a very quick way to visualize data from Python and publication-quality figures in many formats.

pyplot provides a convenient interface to the matplotlib object-oriented plotting library. It is modeled closely after Matlab(TM).

## Simple plot

 *  Define the x-axis and corresponding y-axis values as lists.
 * Plot them on canvas using . plot() function.
 *  Give a name to x-axis and y-axis using . xlabel() and . ylabel() functions.
 * Give a title to your plot using . title() function.
 * Finally, to view your plot, we use . show() function.

 ## Figures, Subplots, Axes and Ticks

 A figure is the windows in the GUI that has "Figure #" as title. Figures are numbered starting from 1 as opposed to the normal Python way starting from 0. 

 With subplot you can arrange plots in a regular grid. 

 Axes are very similar to subplots but allow placement of plots at any location in the figure. 

 There are tick locators to specify where ticks should appear and tick formatters to give ticks the appearance you want.

 ## Animation

 The most easy way to make an animation in matplotlib is to declare a FuncAnimation object that specifies to matplotlib what is the figure to update, what is the update function and what is the delay between frames.

 ### Earthquakes

 We'll now use the rain animation to visualize earthquakes on the planet from the last 30 days. The USGS Earthquake Hazards Program is part of the National Earthquake Hazards Reduction Program (NEHRP) and provides several data on their website. Those data are sorted according to earthquakes magnitude, ranging from significant only down to all earthquakes, major or minor. 