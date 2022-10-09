Add a bunch of interesting charts. 


Simple charts

Install golang - https://go.dev/doc/install
# Steps to Run

```
// Expose the current directory over the browser.
$ go run server.go

```

On your browser go to http://localhost:8080/chart.html to see the chart

# Next Steps

* We have a sample load chart that can scale up with dom elements getting added. 
  >> This is v0 of the UI.

* How can we abstract this in an easy way so that the experience of someone starting out can be made better? 

# Whats the vision?

So chart js gives charts with a little bit of learning. This is essentially an abstraction of that.

Create an element

* lineEasy and define methods data source, xLabel, yLabel
* barEasy and define methods data source, xLabel, yLabel

This repository does the other side. If data is available in a particular 
format that this repo expects. Render it. 

Chart.html will load the data
Make sure you c

