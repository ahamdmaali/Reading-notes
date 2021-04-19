# Charts
#### Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy. 

## To see how to use chart.js we’re going to create a set of 3 graphs :
1. Line chart: show the number of buyers a fictional product.
2. pie chart: show which countries the customers come from.
3. bar chart: show profit over the period.

## Charts Installation
#### You can download the latest version of Chart.js from the [GitHub releases](https://github.com/chartjs/Chart.js/releases/tag/v2.9.4) or use a [Chart.js CDN](https://www.jsdelivr.com/package/npm/chart.js). Detailed installation instructions can be found on the [installation](https://www.chartjs.org/docs/latest/getting-started/installation.html) page.

## Creating a Chart
#### It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.

##### To learn more about craeting a charts, read this article (https://canvas.instructure.com/courses/2568394/discussion_topics/10720003)

# Basic usage of canvas
## Drawing shapes with canvas
### Drawing rectangles
#### Canvas only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

### Drawing paths
####  A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:
1. you create the path.
2. use drawing commands to draw into the path.
3.  stroke or fill the path to render it.

### Moving the pen
#### One very useful function, which doesn't actually draw anything but becomes part of the path list described above, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.

### Lines
#### [ lineTo(x, y) ] Draws a line from the current drawing position to the position specified by x and y.his method takes two arguments, x and y, which are the coordinates of the line's end point. The starting point is dependent on previously drawn paths, where the end point of the previous path is the starting point for the following, etc. The starting point can also be changed by using the moveTo() method.

## Applying styles and colors
### Colors
#### . If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
1. fillStyle = color(Sets the style used when filling shapes).
2. strokeStyle = color(Sets the style for shapes outlines).

### Transparency
#### we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
### globalAlpha = transparencyValue(Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.)

### Using line dashes
#### The setLineDash method and the lineDashOffset property specify the dash pattern for lines. The setLineDash method accepts a list of numbers that specifies distances to alternately draw a line and a gap and the lineDashOffset property sets an offset where to start the pattern.

## Drawing text
#### The canvas rendering context provides two methods to render text:fillText(text, x, y [, maxWidth])Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.strokeText(text, x, y [, maxWidth])Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


