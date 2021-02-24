---
weight: 160
markup: "html"
---
{{< slide bg-color="electric" >}}
# Charts
Thanks to [Chart.js](https://www.chartjs.org/)

------
## Line
{{< chart type="line" >}}
<!--
{
  "data": {
    "labels": [1500, 1600, 1700, 1750, 1800, 1850, 1900, 1950, 1999, 2050],
    "datasets": [{
      "data": [86, 114, 106, 106, 107, 111, 133, 221, 783, 2478],
      "label": "Africa"
    }, {
      "data": [282, 350, 411, 502, 635, 809, 947, 1402, 3700, 5267],
      "label": "Asia"
    }, {
      "data": [168, 170, 178, 190, 203, 276, 408, 547, 675, 734],
      "label": "Europe"
    }, {
      "data": [40, 20, 10, 16, 24, 38, 74, 167, 508, 784],
      "label": "Latin America"
    }, {
      "data": [6, 3, 2, 2, 7, 26, 82, 172, 312, 433],
      "label": "North America"
    }]
  },
  "options": {
    "title": {
      "display": true,
      "text": "World population per region (in millions)"
    }
  }
}
-->
{{< /chart >}}

------
## Line - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="line" >}}
<!--
{
  "data": {
    "labels": [1500, 1600, 1700, 1750, 1800, 1850, 1900, 1950, 1999, 2050],
    "datasets": [{
      "data": [86, 114, 106, 106, 107, 111, 133, 221, 783, 2478],
      "label": "Africa"
    }, {
      "data": [282, 350, 411, 502, 635, 809, 947, 1402, 3700, 5267],
      "label": "Asia"
    }, {
      "data": [168, 170, 178, 190, 203, 276, 408, 547, 675, 734],
      "label": "Europe"
    }, {
      "data": [40, 20, 10, 16, 24, 38, 74, 167, 508, 784],
      "label": "Latin America"
    }, {
      "data": [6, 3, 2, 2, 7, 26, 82, 172, 312, 433],
      "label": "North America"
    }]
  },
  "options": {
    "title": {
      "display": true,
      "text": "World population per region (in millions)"
    }
  }
}
-->
{{< /chart */>}}
{{< /code >}}

------
## Bar
{{< chart type="bar" src="charts/bar.json" />}}

------
## Bar - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="bar" src="charts/bar.json" /*/>}}
{{< /code >}}

------
## Grouped Bar
{{< chart type="bar" src="charts/grouped-bar.json" />}}

------
## Grouped Bar - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="bar" src="charts/grouped-bar.json" /*/>}}
{{< /code >}}

------
## Horizontal Bar
{{< chart type="horizontalBar" src="charts/horizontal-bar.json" />}}

------
## Horizontal Bar - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="horizontalBar" src="charts/horizontal-bar.json" /*/>}}
{{< /code >}}

------
## Pie
{{< chart type="pie" src="charts/pie.json" />}}

------
## Pie - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="pie" src="charts/pie.json" /*/>}}
{{< /code >}}

------
## Doughnut
{{< chart type="doughnut" src="charts/doughnut.json" />}}

------
## Doughnut - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="doughnut" src="charts/doughnut.json" /*/>}}
{{< /code >}}

------
## Radar
{{< chart type="radar" src="charts/radar.json" />}}

------
## Radar - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="radar" src="charts/radar.json" /*/>}}
{{< /code >}}

------
## Polar Area
{{< chart type="polarArea" src="charts/polar-area.json" />}}

------
## Polar Area - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="polarArea" src="charts/polar-area.json" /*/>}}
{{< /code >}}

------
## Bubble
{{< chart type="bubble" src="charts/bubble.json" />}}

------
## Bubble - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="bubble" src="charts/bubble.json" /*/>}}
{{< /code >}}

------
## Scatter
{{< chart type="scatter" src="charts/scatter.json" />}}

------
## Scatter - Source
{{< code lang="markdown" stretch="true" >}}
{{</* chart type="scatter" src="charts/scatter.json" /*/>}}
{{< /code >}}
