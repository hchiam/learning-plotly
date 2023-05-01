# Learning Plotly.js

Just one of the things I'm learning. https://github.com/hchiam/learning

https://www.w3schools.com/js/js_graphics_plotly.asp

https://github.com/plotly/plotly.js/

https://plotly.com/javascript/

```html
<head>
  <script src="https://cdn.plot.ly/plotly-2.22.0.min.js"></script>
</head>
<body>
  <div id="gd"></div>

  <script>
    Plotly.newPlot("gd", {
      data: [{ y: [1, 2, 4] }],
      layout: { width: 600, height: 400 },
    });
  </script>
</body>
```
