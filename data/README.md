---
title: Су ресурстарының картасы
---

<Map
  title="Map"
  layers={[
    {
      "data": "https://opendata.arcgis.com/datasets/9c58741995174fbcb017cf46c8a42f4b_25.geojson",
      "name": "Points",
      "tooltip": true
    },
    {
      "data": "https://d2ad6b4ur7yvpq.cloudfront.net/naturalearth-3.3.0/ne_10m_geography_marine_polys.geojson",
      "name": "Polygons",
      "tooltip": true,
      "colorScale": {
        "starting": "#ff0000",
        "ending": "#00ff00"
      }
    }
  ]}
  center={{
    "latitude": 45,
    "longitude": 0
  }}
  zoom={2}
  autoZoomConfiguration={{
    "layerName": "Points"
  }}
/>
