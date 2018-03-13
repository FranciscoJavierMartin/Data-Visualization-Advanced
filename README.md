# Data visualization - Advanced excercise

This repository contains the code for the advanced excercise for the data visualization module. If you want to see the result [click here](https://franciscojaviermartin.github.io/Data-Visualization-Advanced/).

The goals for this task are:

- Create a line chart.
- Add dots.
- Add interaction.

## index.html
Added a *h1* tag and a *span* for show a detail about the point clicked.

## styles.css
Added a background color to body for a better visualization. A class called *tooltip* has been added to specified the aspect of the tooltip. Inside the tooltip, a *span* tag must be added because doesn't work in the *tooltip* class.

## main.js
A *div* tag has been added to the body and contains the tooltip. The *div* has been opacated with 0 ( it's invisible ) at start.

In front of the line chart, a points chart has been added. The points coincides with the change in the lines. The function that has been executed when the mouse is over a point, show the tooltip next to the point, setting the opacity to .9 with a transation of 200 milliseconds for a better look. The text inside the tooltip shows the month's sales. The tooltip is moved to the left of the point when the cursor pass over any point. When the mouse has been moved out of the point, set the opacity to 0 from hide the tooltip with a transition of 500 milliseconds.

When the user click in a point of the grapic, the detail label up to the graphic is updated with the sales and the month clicked. The date is changed to month name with en-US format.