---
title: Су ресурстарының картасы
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
        ending: '#00ff00',
        starting: '#ff0000'
      },
    },
    {
      data: {
        url: 'https://water.anuveyatsu.com/rivers.geojson',
      },
      name: 'rivers',
      tooltip: true,
      colorScale: {
        ending: '#00ff00',
        starting: '#ff0000'
      },
    }
  ]}
  title='Map test'
  zoom={4}
/>
