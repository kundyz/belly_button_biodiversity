# Belly Button Biodiversity
![logo](/images/logo.jpg)

Task
* Create a PIE chart that uses data from your samples route (/samples/<sample>) to display the top 10 samples.
  * Use sample_values as the values for the PIE chart.
  * Use otu_ids as the labels for the pie chart.
  * Use otu_labels as the hovertext for the chart.
* Create a Bubble Chart that uses data from your samples route (/samples/<sample>) to display each sample.
  * Use otu_ids for the x values.
  * Use sample_values for the y values.
  * Use sample_values for the marker size.
  * Use otu_ids for the marker colors.
  * Use otu_labels for the text values.
* Display the sample metadata from the route /metadata/<sample>.
  * Display each key/value pair from the metadata JSON object somewhere on the page.
* Update all of the plots any time that a new sample is selected.
* You are welcome to create any layout that you would like for your dashboard. An example dashboard page might look something like the following.
* Your dashboard should be unique and original. Place your name in the upper right-hand corner of the window to sign your masterpiece!
* Deploy your Flask app to Heroku.
  * You can use the provided sqlite file for the database.
  * Ask your Instructor and TAs for help!
* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the Weekly Washing Frequency obtained from the route /wfreq/<sample>.
* You will need to modify the example gauge code to account for values ranging from 0 - 9.
* Update the chart whenever a new sample is selected.
* Use Flask API starter code to serve the data needed for your plots.

Output

![logo](/images/Dashboard.png)
![logo](/images/BubbleChart.png)
