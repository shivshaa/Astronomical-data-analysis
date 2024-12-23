# README.md

## Goals and Results

### Main Outcomes

The main outcomes of this project include:

#### Querying and Retrieving Astronomical Data
- Connecting to the Gaia database and retrieving data for specific regions of the sky.
- Writing ADQL (Astronomical Data Query Language) queries for advanced filtering, such as cone searches, polygon searches, and joining multiple datasets.

#### Transforming and Filtering Data
- Using libraries like Astropy and Gala to work with coordinates, units, and coordinate transformations (e.g., converting ICRS coordinates to GD-1’s frame).
- Filtering data for stars that meet specific criteria, such as proximity to GD-1 or specific proper motion values.

#### Storing and Managing Data
- Saving and loading data in formats like FITS and CSV for efficient handling of large datasets.
- Combining photometry and positional data using JOIN operations.

#### Analyzing and Visualizing Data
- Plotting data (e.g., proper motion plots, color-magnitude diagrams) to identify patterns and features of interest.
- Customizing visualizations to make publication-quality figures with annotations and subplots.

#### Identifying GD-1 Stars
- Narrowing down the list of stars likely to belong to the GD-1 stream using proper motion and photometry data.
- Combining spatial, kinematic, and photometric criteria to isolate stars of interest.

## Notebook Highlights

### Notebook 1
- **Goal**: Perform a cone search and retrieve initial data near GD-1.
- **Key Steps**: Connect to Gaia, write a query, and download results.

### Notebook 3
- **Goal**: Transform coordinates and refine the selection of GD-1 stars.
- **Key Steps**: Use proper motion and positional data to filter stars.

### Notebook 5
- **Goal**: Join photometric data with candidate stars for GD-1.
- **Key Steps**: Use JOIN operations and write the output to a file.

### Notebook 6
- **Goal**: Analyze photometry and refine candidate stars based on color-magnitude diagrams.
- **Key Steps**: Merge photometric and positional data into a Pandas DataFrame.

### Notebook 7
- **Goal**: Finalize visualizations for presentation.
- **Key Steps**: Create annotated, multi-panel plots for publication.

## Expected Results

By the end of this project, you should achieve the following:

- A cleaned and filtered dataset of stars belonging to the GD-1 stream.
- A set of publication-quality figures, including proper motion plots and color-magnitude diagrams, that clearly show the properties of GD-1.
- Knowledge of how to query and analyze astronomical data using Python tools like Astropy, Gala, Pandas, and Matplotlib.
- A reproducible workflow for querying and processing data from astronomical databases.
