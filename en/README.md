---
title: Water resources data portal 🇰🇿
---

Water Resources Data Portal is a comprehensive gateway to invaluable data on the country's water landscapes. Rivers, lakes, reservoirs, etc. Immerse yourself in a wealth of carefully curated datasets that provide a panoramic view of Kazakhstan's water resources. Whether you're a researcher, policymaker or environmental enthusiast, our user-friendly platform provides seamless access to critical information about water quality, quantity and usage patterns. Explore dynamic visualizations, conduct in-depth analysis, and uncover actionable insights to drive informed decision-making and sustainable water management practices. Join us on our journey to unlock the potential of Kazakhstan's water resources through data-driven exploration and innovation.

[Map of water resources](/map)

---

## 🔍 Search

<Catalog
  datasets={[
    {
      _id: "aral-sea-area-visualization",
      url_path: 'https://github.com/open-data-kazakhstan/aral-sea-area-visualization',
      metadata: {
        name: 'aral-sea-area-visualization',
        title: 'Aral Sea Area Visualization using Satellite Imagery via Google Earth Engine.'
      }
    },
    {
      _id: "caspian-sea-area-visualization",
      url_path: 'https://github.com/open-data-kazakhstan/caspian-sea-area-visualization',
      metadata: {
        name: 'caspian-sea-area-visualization',
        title: 'The Caspian Sea historical water level data and visualizations since 1992.'
      }
    },
    {
      _id: "water-resources-and-demographics",
      url_path: 'https://github.com/open-data-kazakhstan/water-resources-and-demographics',
      metadata: {
        name: 'water-resources-and-demographics',
        title: 'Water Resources and Demographics Republic of Kazakhstan'
      }
    },
    {
      _id: "terrain-map-kz",
      url_path: 'https://terrain-map-kz.vercel.app/',
      metadata: {
        name: 'terrain-map-kz',
        title: 'Demo terrain map of Kazakhstan'
      }
    }
  ]}
/>

---

## 📈 Highlights

### Aral Sea

<LineChart
  title="Does Aral Sea have a future? Chart shows area in 1000 sq km."
  data={{"url": "https://raw.githubusercontent.com/open-data-kazakhstan/aral-sea-area-visualization/main/data/aral_area.csv"}}
  xAxis="Year"
  yAxis="Total"
/>

Preview raw data:

<FlatUiTable data={{"url": "https://raw.githubusercontent.com/open-data-kazakhstan/aral-sea-area-visualization/main/data/aral_area.csv"}} />

---

### Caspian Sea

<LineChart
  title="Water level in the Caspian Sea relative to sea level."
  data={{"url": "https://raw.githubusercontent.com/open-data-kazakhstan/caspian-sea-area-visualization/main/data/caspian.csv"}}
  xAxis="date"
  yAxis="water level"
/>

Preview raw data:

<FlatUiTable data={{"url": "https://raw.githubusercontent.com/open-data-kazakhstan/caspian-sea-area-visualization/main/data/caspian.csv"}} />
