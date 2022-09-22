# Belly Button Biodiversity

## Background 

In this assignment, an interactive dashboard was built to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.  The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Overview

This analysis aims to accomplish the following:

  1. Read the samples.json using D3 Library.
  2. Develop a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in the individual selected.
     - Use sample_values for bar chart values.
     - Use otu_ids for bar chart labels.
     - Use otu_labels as hovertext for the chart.
  3. Create a bubble chart that displays each sample.
     - Use otu_ids for x values.
     - Use sample_values for y values.
     - Use sample_values for marker size.
     - Use otu_ids for marker colors.
     - Use otu_labels for text values.
  4. Display sample metadata like demographic info for individual.
  5. Display each key-value pair from the metatdata JSON object on the page.
  6. Ability to update the plots when a new sample is selected.
  7. Complete three customizations to the website housing the charts for belly button biodiversity
     - Add an image to the jumbotron.
     - Add background color to webpage.
     - Add more information about the project as a paragraph on the page.
