# QGIS Version History with Coordinates

A comprehensive CSV dataset of QGIS version releases, including geographic coordinates for each codename location.

## About

QGIS versions are named after places where developer meetings or conferences have been held. This repository provides a structured dataset mapping each release to its corresponding geographic location, making it useful for visualizing the global QGIS community or for educational purposes.

## Dataset

The CSV file contains the following fields:

| Field | Description |
|-------|-------------|
| Version | QGIS version number (including LTR designation) |
| Codename | Place name associated with the release |
| Release Date | Official release date (YYYY-MM-DD) |
| Notes | Notable features or changes in the release |
| Latitude | Geographic latitude of the codename location |
| Longitude | Geographic longitude of the codename location |

## Coverage

- **Versions:** 0.0.1-alpha (2002) through 3.44 (2025)
- **Total releases:** 26 versions
- **Locations:** Cities and places across Europe, South America, Asia, Africa, and Oceania

## Sample Data

```csv
Version,Codename,Release Date,Notes,Latitude,Longitude
3.0,Girona,2018-02-23,Significant rewrite upgrading to Qt5 PyQt5 and Python 3.,41.9794,2.8214
3.26,Buenos Aires,2022-06-17,Improved pointcloud and 3D support. New profile plotting framework.,-34.6037,-58.3816
3.40 LTR,Bratislava,2024-10-25,,48.1486,17.1077
```

## Usage

Load the CSV into QGIS, Python, R, or any GIS/data analysis tool:

```python
import pandas as pd
df = pd.read_csv('qgis_version_history.csv')
```

```r
data <- read.csv('qgis_version_history.csv')
```

## Notes

- Some entries (e.g., version 0.0.1-alpha, 3.14 "Pi") do not have coordinates as they are not place names
- "Kore" refers to Seoul, South Korea
- "Dufour" refers to the Dufourspitze peak in the Swiss Alps

## License

This dataset is provided for educational and informational purposes. QGIS is a free and open-source Geographic Information System licensed under the GNU GPL.

## Links

- [QGIS Official Website](https://qgis.org)
- [QGIS GitHub Repository](https://github.com/qgis/QGIS)

## Contributing

Feel free to open an issue or submit a pull request if you find any errors or would like to add additional information.
