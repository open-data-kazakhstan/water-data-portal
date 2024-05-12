---
title: Су ресурстарының картасы
---

<Map
  center={{
    latitude: 45,
    longitude: 0
  }}
  layers={[
    {
      data: {
        url: 'https://opendata.arcgis.com/datasets/9c58741995174fbcb017cf46c8a42f4b_25.geojson',
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
  zoom={2}
/>
