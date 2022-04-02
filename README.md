# plot.ly-challenge
HW # 14 Plot.ly - Belly Button Biodiveristy



![Bacteria by filterforge.com](Images/bacteria.jpg)

This assignment required us to build an interactive dashboard using D3 library, . It explores the microbes that colonize human navels. 

Data Source:
[Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/)

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.
![Screenshot of Bar Chart](https://user-images.githubusercontent.com/94502554/161396078-4bd0714e-e93e-4658-9b08-c9de3c5758a6.png)

3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.

![Screenshot of Bubble Chart](https://user-images.githubusercontent.com/94502554/161396085-e1b02365-ff81-4641-82ca-00eecf6cdd8c.png)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

6. Update all of the plots any time that a new sample is selected.

Full Dashboard view:
![Screenshot of Dashboard](https://user-images.githubusercontent.com/94502554/161396127-e0958ae0-8ed8-4881-8ec4-52b2c0af5425.png)



