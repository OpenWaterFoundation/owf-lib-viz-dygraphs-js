 # owf-lib-viz-dygraphs
Open Water Foundation visualization library based on Dygraphs

## Getting Started

A standard development folder structure is recommended. The website development files can be set up as follows (Windows is assumed, but Linux would be similar):

```
> C:
> cd \Users\user
> mkdir Dygraphs-JS
> cd Dygraphs-JS
> mkdir git-repos
> cd git-repos
> git clone https://github.com/OpenWaterFoundation/owf-lib-viz-dygraphs-js
``` 
This repository contains three different folders. Each folder contains an example of how to create a Time Series chart using Dygraphs. In order to see each example, download or clone this repository and open up each examples index.html in a web browser of your choosing. For further documentation on each folder refer to the links below:

* [TS-Tool-Large-Data-Example](https://github.com/OpenWaterFoundation/owf-lib-viz-dygraphs-js/tree/master/TS-Tool-Large-Data-Example)
* [TS-Tool-Small-Data-Example](https://github.com/OpenWaterFoundation/owf-lib-viz-dygraphs-js/tree/master/TS-Tool-Small-Data-Example)
* [simple-example](https://github.com/OpenWaterFoundation/owf-lib-viz-dygraphs-js/tree/master/simple-example)

## Additional Documentation

See also:
* [Dygraphs Documentation](http://dygraphs.com/tutorial.html)
* [Dygraphs Options Documentation](http://dygraphs.com/options.html)
* [Dygraphs API Reference](http://dygraphs.com/jsdoc/symbols/Dygraph.html)

## Data Format RCC-ACIS Precipitation Time Series
|Date   |StationID 1   |StationID 2   |StationID 3   |StationID X   |
|:-:|---|---|---|---|
|1/01/2000   |0.0   |1.0   |0.0   |precipitation amount   |
|1/02/2000   |0.5   |1.73   |0.2   |precipitation amount   |
|1/03/2000   |0.26   |0.84   |0.64   |precipitation amount   |

** **Note** the data below each station is the amount of precipitation that occured that day. 

## NOTES

* Dygraph charts had issues with being mobile friendly when using bootstrap on the html page. Refer to [Bootstrap Repo](https://github.com/OpenWaterFoundation/owf-lib-viz-bootstrap-js) for workaround.
* Found this forum on Google Code that talks about this issue. [Google Code](https://code.google.com/archive/p/dygraphs/issues/238).
* Requires small amount of code to implement 
* Provides examples and documentation
* Open Source
* Free
* Has a good release history
* Actively developed

## What is a Timeseries Graph

Timeseries, also known as Line Graphs, are used to display quantitative value over a continuous interval or time span. It is most frequently used to show trends and relationships (when grouped with other lines). Line Graphs also help to give a "big picture" over an interval, to see how it has developed over that period.

Line Graphs are drawn by first plotting data points on a Cartesian coordinate grid, then connecting a line between these points. Typically, the y-axis has a quantitative value, while the x-axis has either a category or sequenced scale. Negative values can be displayed below the x-axis.

For more information refer to the links below:

* [Timeseries Graph](http://www.datavizcatalogue.com/methods/line_graph.html)
* [Timeseries Documenation](https://developers.google.com/chart/interactive/docs/gallery/linechart)