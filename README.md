# Signal Analysis Dashboard

A web-based tool for analyzing multi-channel signal data from CSV files.

## Features

- **Single Analysis Mode**: Analyze selected channels with detailed controls
- **Multi-Channel View**: View all channels simultaneously in a grid layout
- **Real-time Processing**: Handle large CSV files with automatic downsampling
- **Interactive Charts**: Zoom, pan, and explore your data
- **Dark/Light Theme**: Optimized viewing for different analysis modes

## Live Demo

Visit: https://SuwanneeThongtha.github.io/signal-analysis-dashboard/

## Usage

1. Click "Choose CSV File" to upload your data
2. Select analysis mode (Single or Multi-Channel)
3. Configure display options
4. Click "Update" to refresh the visualization

## CSV Format

Your CSV file should have the following structure:
- `Counter` column (for x-axis)
- `Signal_CH1`, `Signal_CH2`, ... `Signal_CHn` columns (for signal data)

## Technologies Used

- Chart.js for data visualization
- PapaParse for CSV parsing
- Pure JavaScript (no framework dependencies)

## License

MIT License
