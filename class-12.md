# Chart.js, Canvas API

## Chart.js 

[Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

- simple .js charting software, free open-source .js library for data visualization
- .js plugin that uses HTML5 canvas element to make a graph
- download, import script Chart.min.js
- create canvas element in HTML - allows Chart.js to draw the chart
  - give height and width
- grab context of canvas element via .js (see article)
- create data for values of the chart
- can draw graphs, pie charts, bar charts, etc.

[Chart.js Documentation](https://www.chartjs.org/docs/latest/)

## Canvas API

[MDN: Basic Usage of Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
- canvas element: `<canvas id="" width="" height=""></canvas>`
  - will be 300px wide and 150px if no width/height set
  - CSS will need to consider the default sizing or the chart will look distorted
  - additional CSS styling wont impact the chart drawing
- define fallback for older browsers
- canvas represents a rendering context
- rendering context is used in .js to create and manipulate chart content

[MDN: Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

[MDN: Applying Styles and Colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

[MDN: Draw Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)





