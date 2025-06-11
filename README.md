# GTFS Agency Selection Plugin

## Overview

The GTFS Agency Selection Plugin is a tool for QGIS that allows users to filter and extract data for specific public transport agencies from GTFS (General Transit Feed Specification) files. This plugin enables users to create a new folder containing GTFS files tailored to the selected agencies, facilitating routing and analysis in OpenStreetMap (OSM) or other GIS platforms.

## Features

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

## Requirements

- QGIS 3.x
- Python dependencies: `pandas`

## License

This plugin is licensed under the GNU General Public License v2.0 or later.

## Author

- **Luigi Dalbosco**
- Email: luigi.dalbosco@gmail.com
