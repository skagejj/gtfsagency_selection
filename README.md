# GTFS Agency Selection Plugin
The first of one of the FlowRide Plugins

## Overview
The GTFS Agency Selection Plugin is a tool for QGIS that allows users to filter and extract data for specific public transport agencies from GTFS (General Transit Feed Specification) files. This plugin enables users to create a new folder containing GTFS files tailored to the selected agencies, facilitating routing and analysis in OpenStreetMap (OSM) or other GIS platforms.

## Plugin Series

This plugin is the second in a series of four plugins designed to work together for comprehensive public transport analysis:
1. **GTFS Agency Selection** ([GitHub Repository](https://github.com/skagejj/gtfsagency_selection)): Focuses on selecting and filtering GTFS data for specific agencies.
2. **OSM Import Roads and Public Transport Stops** (This Plugin): Handles the import and integration of OSM road and stop data with GTFS datasets.
3. **OSM PT Routing** ([GitHub Repository](https://github.com/skagejj/osm_pt_routing)): Provides advanced routing capabilities using the processed OSM and GTFS data.
4. **GTFS Shapes Tracer** ([GitHub Repository](https://github.com/skagejj/gtfs_shapes_tracer)): Generates GTFS shapes based on spatial data for accurate route visualization.

## Usage

1. **Import Roads and Stops**: Use the plugin to download and process OSM road and stop data for your city.
2. **Enhance GTFS Data**: Match GTFS stops with OSM stops and enrich GTFS datasets with spatial attributes.
3. **Prepare Routing Layers**: Generate layers optimized for routing analysis, including stop positions and road segments.

## Teasing
Watch the teasing for these plugin [here](https://drive.google.com/file/d/1oaudC09QLDbCJ0qPIztnBvTf7KJRwrF7/view?usp=sharing).

## Features of GTFS Agency Selection Plugin

- **Agency Selection**: Choose one or more public transport agencies from the GTFS dataset.
- **Filtered GTFS Files**: Generate a new folder containing GTFS files (`agency.txt`, `routes.txt`, `trips.txt`, `stop_times.txt`, `stops.txt`, `calendar.txt`, and `calendar_dates.txt`) filtered for the selected agencies.
- **Interactive Search**: Search for agencies using a text input field.
- **User-Friendly Interface**: Intuitive dialog for selecting agencies and specifying the output directory.

## How It Works

1. **Load GTFS Data**: The plugin reads GTFS files from the specified directory.
2. **Select Agencies**: Users can select agencies from a list or search for specific ones.
3. **Generate Output**: The plugin creates a new folder containing filtered GTFS files for the selected agencies.

## Installation

1. Download and install the plugin in QGIS.
2. Ensure the GTFS files (`agency.txt`, `routes.txt`, `trips.txt`, `stop_times.txt`, `stops.txt`, `calendar.txt`, and `calendar_dates.txt`) are available in the specified directory.

## Usage

1. Open the plugin from the QGIS toolbar.
2. Specify the directory containing the GTFS files.
3. Select the desired agencies from the list or search for them.
4. Click the "Update Agencies" button to refresh the list.
5. Click "OK" to generate the filtered GTFS files in a new folder.

## Explanation Video

For a detailed walkthrough of how to use the GTFS Agency Selection Plugin, watch the explanation video [here](https://drive.google.com/file/d/1-LpZNxSGjI7SOaZ7Hn3MHk-4omOrxm9-/view?usp=sharing).


## Requirements

- QGIS 3.x
- Python dependencies: `pandas`

## License

This plugin is licensed under the GNU General Public License v2.0 or later.

## Author

- **Luigi Dalbosco**
- Email: luigi.dalbosco@gmail.com
