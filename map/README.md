---
title: Су ресурстарының картасы 🗺  Map view of water resources
---

<Map
  center={{
    latitude: 48,
    longitude: 66
  }}
  layers={[
    {
      data: {
        url: 'https://water.anuveyatsu.com/basin.geojson',
      },
      name: 'basin',
      colorScale: {
        ending: '#2AD587',
        starting: '#8EE80E'
      }
    }
  ]}
  title='Map'
  zoom={4}
/>
