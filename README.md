Add a bunch of interesting charts. 


Simple charts

Install golang - https://go.dev/doc/install
# Steps to Run

```
// Expose the current directory over the browser.
$ go run server.go

```

On your browser go to http://localhost:8080/chart.html to see the chart

# Whats the vision?

So chart js gives charts with a little bit of learning. This is essentially an abstraction of that.

Create an element

* lineEasy and define methods data source, xLabel, yLabel
* barEasy and define methods data source, xLabel, yLabel

This repository does the other side. If data is available in a particular 
format that this repo expects. Render it. 

Chart.html will load the data
Make sure you c

