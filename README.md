# GPS Route Tracker

This Python project visualizes GPS route data by processing coordinates (latitude and longitude) from a CSV file. The route is plotted on a Google Map using the `gmplot` library, and the final map is saved as an HTML file for easy visualization.

## Features

- Reads GPS data from a CSV file containing latitude and longitude.
- Plots the GPS route on a Google Map.
- Saves the map as an HTML file for interactive viewing.
- Simple, easy-to-use, and customizable visualization.

## Prerequisites

Before running the project, make sure you have the following libraries installed:

- `pandas` for handling and processing the GPS data.
- `gmplot` for plotting the route on Google Maps.

You can install them using pip:

```bash
pip install pandas gmplot
```

## Dataset

The project requires a CSV file containing GPS coordinates in the following format:

```csv
latitude,longitude
12.9716,77.5946
12.9756,77.6050
12.9806,77.6175
12.9830,77.6300
```

You can use your own dataset or download the sample dataset from [gps_data.csv](./gps_data.csv).

## How to Run

1. Download the CSV file with GPS coordinates.
2. Save the file as `gps_data.csv` or update the path in the code accordingly.
3. Run the Python script.

```bash
python gps_route_tracker.py
```

4. The route will be plotted on a Google Map and saved as `gps_route_map.html`.
5. Open the `gps_route_map.html` file in any web browser to view the interactive map.

## Example Output

Once the script is executed, you will have an HTML file (`gps_route_map.html`) that contains the visualized route. Open this file in your browser to view the plotted GPS route.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
