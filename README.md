---
title: Су ресурстарының деректер порталы 🇰🇿
---

Қазақстанның су ресурстарының деректер порталы – елдегі су ландшафттары туралы баға жетпес деректерге арналған жан-жақты шлюз. Өзендер, көлдер, су қоймалары және т.б. қамтитын, Қазақстанның су ресурстарының панорамалық көрінісін ұсынатын, мұқият құрастырылған деректер жиынтығының байлығына сүңгіңіз. Сіз зерттеуші, саясаткер немесе қоршаған ортаға әуесқой болсаңыз да, біздің пайдаланушыға ыңғайлы платформамыз судың сапасы, саны және пайдалану үлгілері туралы маңызды ақпаратқа үздіксіз қол жеткізуді қамтамасыз етеді. Динамикалық визуализацияларды зерттеңіз, терең талдаулар жүргізіңіз және ақпараттандырылған шешім қабылдауға және суды басқарудың тұрақты тәжірибесіне ықпал ету үшін әрекет етуге болатын түсініктерді ашыңыз. Деректерге негізделген барлау және инновациялар арқылы Қазақстанның су ресурстарының әлеуетін ашу үшін бізге саяхатқа қосылыңыз.

[Су ресурстарының картасы](./data)

## іздеңіз

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

## шолу

### Арал теңізі

<LineChart
  title="Арал теңізінің болашағы бар ма? Диаграмма 1000 шаршы км аумақты көрсетеді."
  data="https://raw.githubusercontent.com/open-data-kazakhstan/aral-sea-area-visualization/main/data/aral_area.csv"
  xAxis="Year"
  yAxis="Total"
/>

Шикі деректерді қарау:

<FlatUiTable url="https://raw.githubusercontent.com/open-data-kazakhstan/aral-sea-area-visualization/main/data/aral_area.csv" />

### Каспий теңізі

<LineChart
  title="Теңіз деңгейіне қатысты Каспий теңізіндегі су деңгейі."
  data="https://raw.githubusercontent.com/open-data-kazakhstan/caspian-sea-area-visualization/main/data/caspian.csv"
  xAxis="date"
  yAxis="water level"
/>

Шикі деректерді қарау:

<FlatUiTable url="https://raw.githubusercontent.com/open-data-kazakhstan/caspian-sea-area-visualization/main/data/caspian.csv" />
