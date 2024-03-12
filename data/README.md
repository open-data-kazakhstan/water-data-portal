# Су ресурстарының картасы

<Map
  title="Map"
  layers={[
    {
      "data": "./rivers.geojson",
      "name": "rivers",
      "tooltip": false
    },
    {
      "data": "data/side_inflow.geojson",
      "name": "side_inflow",
      "tooltip": false
    }
  ]}
  center={{
    latitude: 43.3501919326,
    longitude: 79.0748797005
  }}
  zoom={5}
/>