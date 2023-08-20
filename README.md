# Belly Button Biodiversity Dataset Interactive Dashboard

## Background
This project is focused on building an interactive dashboard exploring the Belly Button Biodiversity Dataset. This dataset catalogs the microbes that colonize human navels. It reveals that a small handful of microbial species(also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Tools Used
- `d3.js`
- `plot.ly`
- `HTML`

## Requirements Delivered

### Created Bar Charts
- Created a bar chart to update a new sample selected
- Created a bar chart that uses Top 10 sample values as values
- Chart uses `otu_ids` as the labels 
- Chart uses `otu_labels` as the tooltip

### Created Bubble Charts
- Chart updates when a new sample is selected
- Chart uses `otu_ids` for the x values 
- Chart uses `otu_ids` for marker colors
- Chart uses `sample_values` for the y values
- Chart uses `sample_values` for the marker size
- Chart uses `otu_labels` for text values

### Metadata and Deployment
- Metadata initializes without error
- Metadata updates when a new sample is selected
- App Successfully Deployed to Github Pages 
