# Earthquake_ML
Earthquakes are catastrophic natural events that can result in extensive damage and loss of lives. Predicting earthquakes with precision is crucial for creating effective early warning systems, enhancing disaster preparedness, conducting risk evaluations, and advancing scientific understanding. This project focuses on forecasting the magnitude and likelihood of earthquakes occurring in a specific region (California, United States) by leveraging historical earthquake data and employing various machine learning models.

Dataset
The dataset utilized for this project is the "SOCR Earthquake Dataset," which provides detailed records of earthquakes with magnitudes of 3.0 or higher in California, United States. Each entry in the dataset corresponds to a single earthquake event and includes the following attributes:

Date and time: Recorded in UTC (Coordinated Universal Time)
Latitude and longitude: Coordinates (in degrees) pinpointing the earthquake’s epicenter, the surface point directly above its origin
Depth: Measured in kilometers, indicating how far below the surface the earthquake occurred
Magnitude: Represented on the logarithmic Richter scale
SRC: Data source identifier
nst: Number of stations contributing to the solution (range: 0 to ...)
close: Distance to the nearest station from the epicenter (range: 0 to ...)
rms: Root-mean-squared residual of the solution (range: 0.0 to 1.0)
gap: Azimuthal gap in degrees (range: 0 to 360)
The Richter scale quantifies earthquake magnitude based on the energy released, with each unit increase indicating a tenfold rise in the amplitude of seismic waves.

This dataset encompasses earthquake occurrences between January 2, 2017, and December 31, 2019, totaling 37,706 events. It holds potential for diverse applications, such as analyzing earthquake patterns, identifying trends over time, or forecasting future seismic activities.
