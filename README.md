# Belly Button Biodiversity Dashboard

## Project Overview
This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the types and abundances of microbes found in human navels. This dashboard visualizes microbial species, known as operational taxonomic units (OTUs), which vary significantly across individuals. The dataset reveals that a small number of microbial species are prevalent in over 70% of people, while most species are relatively rare.

### Features
The dashboard includes the following interactive features:

Dropdown Menu: Allows users to select a specific individual’s sample from the dataset.
Bar Chart: Displays the top 10 OTUs found in the selected individual.
X-axis: Represents the abundance of each OTU.
Y-axis: Lists OTU IDs.
Hovertext: Displays the OTU labels for each bar.
Bubble Chart: Shows the distribution of all OTUs in the sample.
X-axis: OTU IDs.
Y-axis: Abundance values (sample values).
Demographic Information Panel: Shows metadata for the selected individual, including demographic information such as age, gender, and location.
How It Works
The dashboard dynamically updates each visualization when a new sample is selected. The data is sourced directly from an external JSON file using the D3.js library, ensuring a smooth, interactive experience.

Deployment
The application is deployed as a static website using GitHub Pages. You can view the live dashboard here.

License
This project is for educational purposes and follows the licensing terms provided by the data source.
