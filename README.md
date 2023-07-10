# belly_button_challenge

Background
--------
Build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

## Objective ##
- Use the D3 library to read in `samples.json` from the URL
- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual with:
  - `sample_values` as the values for the bar chart.
  - `otu_ids` as the labels for the bar chart.
  - `otu_labels` as the hovertext for the chart.
    
- Create a bubble chart that displays each sample with:
  - `otu_ids` for the x values.
  - `sample_values` for the y values.
  - `sample_values` for the marker size.
  - `otu_ids` for the marker colors.
  - `otu_labels` for the text values.
 
- Display the sample metadata, i.e., an individual's demographic information.
- Display each key-value pair from the metadata JSON object somewhere on the page.
- Update all the plots when a new sample is selected.
- Deploy your app to a free static page hosting service, link can be found here.
