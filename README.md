# Seabed Topography Data

This repository contains underwater terrain data obtained from real measured water depth data. The data has been preprocessed and is available in Excel format. The dataset includes coordinates and water depth, and is intended for use in various scientific and engineering applications, such as oceanography, marine research, and environmental studies.

## Dataset Description

The dataset consists of three variables:

- **Xi**: The horizontal coordinate (X-axis) of the seabed in kilometers.
- **Yi**: The horizontal coordinate (Y-axis) of the seabed in kilometers.
- **Zi**: The water depth at the corresponding (Xi, Yi) coordinates in meters.

### Units:
- **Xi and Yi**: Kilometers
- **Zi**: Meters (represents water depth)

## Data Structure

The data is stored in Excel tables with the following columns:
- **Xi (km)**: X-coordinate of the seabed point.
- **Yi (km)**: Y-coordinate of the seabed point.
- **Zi (m)**: Water depth at the respective coordinates.

## Usage

This dataset can be loaded into various programming languages for analysis, visualization, and modeling. Some common use cases include:
- Visualizing the underwater terrain and depth contours.
- Analyzing seabed morphology and topography.
- Modeling and simulating oceanographic processes.

You can easily import this data into Python, R, MATLAB, or other data processing environments. For example, in Python, you can use the `pandas` library to read the data from the Excel file:

```python
import pandas as pd

# Load the seabed topography data
data = pd.read_excel('UnderwaterTerrain_AA.xlsx')
# Display the first few rows of the dataset
print(data.head())
```

## CHANGELOG

### [v1.0.0] - 2022-06-28
-The most original sparse data has been released.

### [v1.0.1] - 2023-11-03
-v1.0.0 was deleted and the preprocessed ten types of underwater terrain data were updated.

### [v1.0.2] - 2025-5-13
-v1.0.1 was deleted and all data was written into the standard excel files. Instructions for reading data were added.
