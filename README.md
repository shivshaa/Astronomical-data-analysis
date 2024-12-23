# README.md

## Goals and Results

### Main Outcomes

The main outcomes of this project include:

### Notebook 1: Introduction to Database Queries
- Task: Connecting to the Gaia database, exploring available data tables, writing queries, and downloading data as an Astropy Table.
- Result: You’ll gain experience in querying astronomical databases and storing the results in a structured format for analysis.

## Notebook 2: Cone Search and Star Selection
-Task: Performing a "cone search" (selecting stars in a circular region of the sky), using units with Quantity objects, converting coordinates with Gala, and selecting stars within a polygon.
-Result: You'll obtain star data within specific regions of the sky and store the results in a FITS file for further use.

## Notebook 3: Coordinate Transformation and Star Selection
-Task: Loading the data saved in the previous notebook, transforming coordinates and proper motion, and identifying stars near GD-1’s centerline based on proper motion.
-Result: A dataset of stars with proper motion values that are likely part of the GD-1 structure, ready for visualization.

## Notebook 4: Filtering Stars Based on Proper Motion
-Task: Using ADQL queries to filter stars based on proper motion and storing the data in a CSV file.
-Result: A refined list of stars that can be used for more focused analysis or larger searches across the sky.

## Notebook 5: Joining with Photometry Data
-Task: Using a JOIN operation to combine the star candidates from the previous step with photometry data (like color and brightness).
-Result: You’ll enrich your dataset with photometric information, preparing for further analysis.

## Notebook 6: Creating a Color-Magnitude Diagram
-Task: Generating a color-magnitude diagram (CMD) using the photometry data and selecting stars within a specific region of the diagram.
-Result: A clearer view of the stars you’re working with, which can be used to identify key features and select specific subsets of stars for further study.

## Notebook 7: Enhancing Figures and Customization
-Task: Improving the presentation of your CMD by adding annotations, customizing visual elements, and creating multi-panel figures.
-Result: High-quality, publication-ready visualizations that can clearly present your findings.

## Expected Results

By the end of this project, you should achieve the following:

- A cleaned and filtered dataset of stars belonging to the GD-1 stream.
- A set of publication-quality figures, including proper motion plots and color-magnitude diagrams, that clearly show the properties of GD-1.
- Knowledge of how to query and analyze astronomical data using Python tools like Astropy, Gala, Pandas, and Matplotlib.
- A reproducible workflow for querying and processing data from astronomical databases.
