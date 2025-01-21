# Belly Button Biodiversity Dashboard

## Summary
This project involves the analysis and visualization of belly button biodiversity data using D3.js and Plotly.js libraries. The goal is to create interactive charts showing OTUs (Operational Taxonomic Units) found in individual samples and deploy the application on GitHub Pages.

## Objectives
- Read data from a JSON file using the D3.js library.
- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in each sample.
- Create a bubble chart displaying each sample.
- Display the sample's metadata, i.e., the individual's demographic information.
- Update all charts and metadata when a new sample is selected.
- Deploy the application to a free static page hosting service like GitHub Pages.

## Data Description
The dataset includes:
- **samples.json**: Information about various OTUs found in the samples, including their IDs, values, and labels.

## Included Scripts
1. **app.js**: 
   - Reads data from `samples.json`.
   - Creates and updates the bar and bubble charts with OTUs.
   - Displays and updates the metadata for the selected samples.
   - Initializes the page and handles dropdown menu events.

2. **index.html**: 
   - Structures the webpage and defines where the charts and metadata information are displayed.
   - Includes references to the D3.js and Plotly.js libraries.

## Requirements
- D3.js
- Plotly.js

## Instructions

### Getting Started
1. Ensure you have an internet connection to load the D3.js and Plotly.js libraries.
2. Open `index.html` in your browser.

### Features
- **Dropdown Menu**: Select a sample from the dropdown menu to update the charts and metadata information.
- **Bar Chart**: Displays the top 10 OTUs found in the selected sample.
- **Bubble Chart**: Displays all OTUs for the selected sample with sizes and colors proportional to their values.
- **Metadata Information**: Displays the demographic information of the individual.

## Deployment
The application is deployed on GitHub Pages. You can access it [here](https://fjdpr.github.io/belly-button-challenge/).

## References
Hulcr, J. et al. (2012) A jungle in there: bacteria in belly buttons are highly diverse, but predictable. Retrieved from: [Belly Button Biodiversity](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
