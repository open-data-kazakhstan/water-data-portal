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
        url: 'https://water.anuveyatsu.com/side_inflow.geojson',
      },
      name: 'side_inflow',
      tooltip: true,
      colorScale: {
        ending: '#5000A8',
        starting: '#8700AA'
      },
    },
    {
      data: {
        url: 'https://water.anuveyatsu.com/rivers.geojson',
      },
      name: 'rivers',
      tooltip: true,
      colorScale: {
        ending: '#5000A8',
        starting: '#8700AA'
      },
    },
    {
      data: {
        url: 'https://water.anuveyatsu.com/basin.geojson',
      },
      name: 'basin',
      tooltip: true,
      colorScale: {
        ending: '#2AD587',
        starting: '#8EE80E'
      },
    }
  ]}
  title='Map'
  zoom={4}
  style={{height: 800}}
/>
