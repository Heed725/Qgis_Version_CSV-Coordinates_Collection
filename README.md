# QGIS Version History with Coordinates

![QGIS](https://img.shields.io/badge/QGIS-3.44-93b023?style=for-the-badge&logo=qgis&logoColor=white)
![License](https://img.shields.io/badge/License-Open%20Data-blue?style=for-the-badge)
![CSV](https://img.shields.io/badge/Format-CSV-green?style=for-the-badge)
![Locations](https://img.shields.io/badge/Locations-26-orange?style=for-the-badge)

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/QGIS_logo_new.svg" alt="QGIS Logo" width="200"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-❤️%20for%20GIS-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Open%20Source-💚-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/Coordinates-🌍-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/QGIS-🗺️%20sketching%20the%20World-93b023?style=flat-square"/>
</p>

---

## 🌍 About

A comprehensive CSV dataset of QGIS version releases, including geographic coordinates for each codename location.

QGIS versions are named after places where developer meetings or conferences have been held. This repository provides a structured dataset mapping each release to its corresponding geographic location, making it useful for visualizing the global QGIS community or for educational purposes.

<p align="center">
  <img src="https://img.shields.io/badge/QGIS-Free%20%26%20Open%20Source%20GIS-93b023?style=for-the-badge&logo=qgis&logoColor=white"/>
</p>

---

## 📊 Dataset

The CSV file contains the following fields:

| Field | Description |
|-------|-------------|
| Version | QGIS version number (including LTR designation) |
| Codename | Place name associated with the release |
| Release Date | Official release date (YYYY-MM-DD) |
| Notes | Notable features or changes in the release |
| Latitude | Geographic latitude of the codename location |
| Longitude | Geographic longitude of the codename location |

---

## 🗺️ Coverage

<p align="center">
  <img src="https://img.shields.io/badge/Europe-🇪🇺-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/South%20America-🌎-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Asia-🌏-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Africa-🌍-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/Oceania-🏝️-cyan?style=flat-square"/>
</p>

- **Versions:** 0.0.1-alpha (2002) through 3.44 (2025)
- **Total releases:** 26 versions
- **Locations:** Cities and places across Europe, South America, Asia, Africa, and Oceania

---

## 📝 Sample Data

```csv
Version,Codename,Release Date,Notes,Latitude,Longitude
3.0,Girona,2018-02-23,Significant rewrite upgrading to Qt5 PyQt5 and Python 3.,41.9794,2.8214
3.26,Buenos Aires,2022-06-17,Improved pointcloud and 3D support. New profile plotting framework.,-34.6037,-58.3816
3.40 LTR,Bratislava,2024-10-25,,48.1486,17.1077
```

---

## 💻 Usage

Load the CSV into QGIS, Python, R, or any GIS/data analysis tool:

**Python:**
```python
import pandas as pd
df = pd.read_csv('qgis_version_history.csv')
```

**R:**
```r
data <- read.csv('qgis_version_history.csv')
```

**QGIS:**
1. Open QGIS
2. Go to `Layer` → `Add Layer` → `Add Delimited Text Layer`
3. Select the CSV file
4. Set X field to `Longitude` and Y field to `Latitude`
5. Click `Add` to visualize the locations!

---

## 📌 Notes

- Some entries (e.g., version 0.0.1-alpha, 3.14 "Pi") do not have coordinates as they are not place names
- "Kore" refers to Seoul, South Korea
- "Dufour" refers to the Dufourspitze peak in the Swiss Alps

---

## 🔗 Links

<p align="center">
  <a href="https://qgis.org">
    <img src="https://img.shields.io/badge/QGIS-Official%20Website-93b023?style=for-the-badge&logo=qgis&logoColor=white"/>
  </a>
  <a href="https://github.com/qgis/QGIS">
    <img src="https://img.shields.io/badge/QGIS-GitHub%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 📜 License

![License](https://img.shields.io/badge/License-Open%20Data-blue?style=flat-square)

This dataset is provided for educational and informational purposes. QGIS is a free and open-source Geographic Information System licensed under the GNU GPL.

---

## 🤝 Contributing

Feel free to open an issue or submit a pull request if you find any errors or would like to add additional information.

<p align="center">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Issues-Welcome-blue?style=for-the-badge"/>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-QGIS%20💚-93b023?style=for-the-badge&logo=qgis&logoColor=white"/>
</p>

<p align="center">
  <i>Sketching the world, one version at a time 🌍</i>
</p>
