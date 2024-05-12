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
      name: 'Points',
      tooltip: true,
      colorScale: {
        ending: '#00ff00',
        starting: '#ff0000'
      },
    }
  ]}
  title='Map test'
  zoom={3}
/>
