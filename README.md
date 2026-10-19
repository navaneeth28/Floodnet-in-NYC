# FloodNet in NYC: Descriptive Flood-Event Analysis

## Project Overview

This project analyzes flood events recorded by the FloodNet sensor network in New York City. It focuses on identifying events with greater flood depth and longer duration, and comparing observed event patterns across monitored sensor locations.

## Research Question

Which monitored FloodNet sensor locations recorded higher rates of severe and persistent flood events in the analyzed dataset snapshot?

## Data

The repository includes a cleaned event-level dataset used for the descriptive analysis. The dataset contains flood-event measurements, timestamps, sensor locations, flood depth, duration, and derived event indicators.

**Data limitation:** The included dataset is a saved snapshot from August 2026. It may not reflect the latest version of the public FloodNet dataset.

## Methodology

The analysis uses descriptive statistics and sensor-level comparisons.

For this project, an event is defined as:

- **Severe:** maximum flood depth of at least 4 inches.
- **Persistent:** total flood duration of at least 120 minutes.
- **Severe and persistent:** meets both criteria.

Sensor-level rates are normalized by recorded deployment days where available. These rates describe the observed dataset and are not probabilities of future flooding.

## Repository Files

- `FloodNet_Descriptive_Analysis.ipynb` — descriptive analysis notebook.
- `FloodNet_clean_event_dataset.csv` — cleaned event-level dataset snapshot.
- Final presentation (`.pptx`) — project findings, interpretation, and limitations.

## Limitations

FloodNet sensors are not necessarily placed randomly across the city. Differences between sensors may reflect sensor placement, deployment duration, local conditions, and data quality. Therefore, the results should not be interpreted as a definitive ranking of flood risk across all NYC neighborhoods or as proof of causation.

The notebook documents the descriptive analysis performed using the saved dataset snapshot. It does not, by itself, reproduce every upstream data-cleaning step or any separate adjusted statistical model.

## Reproducibility

Open the Jupyter notebook in this repository to review the analysis and its documented assumptions. Results should be interpreted in the context of the dataset snapshot and limitations described above.
