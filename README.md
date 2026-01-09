# Daily-Birth-Statistics-Mapped-to-Zodiac-Signs
Independent research on daily birth distributions: comparing calendar aggregation vs. solar-ecliptic (360°) aggregation using ephemerides.
Project: Birth Distribution: Calendar vs. Solar-Ecliptic Aggregation

Goal: Compare daily births aggregation in (a) calendar time and (b) solar-ecliptic (360°) time using ephemerides-based solar longitude mapping.

Key idea: The same daily birth series can be regrouped by equal solar-longitude segments (e.g., 12×30°) instead of calendar months. This repository documents the pipeline and provides reproducible analysis.
Disclaimer: This is a statistical/methodological observation and does not claim causal mechanisms.

## Data availability

Raw and processed daily birth datasets are hosted on Kaggle due to size and licensing constraints.
Kaggle dataset:https://www.kaggle.com/datasets/innaklymenko/daily-birth-statistics-mapped-to-zodiac-signs

## Methodology Overview 

Zodiac signs are assigned using the tropical zodiac system, based on the geocentric apparent position of the Sun relative to the Earth. The zero point of the zodiac is defined by the vernal (spring) equinox. Each zodiac sign corresponds to a 30-degree segment of the ecliptic, measured sequentially from the vernal equinox. Each calendar date is mapped to exactly one zodiac sign and one element. All dates are treated uniformly; time of birth and geographic location are not considered. Daily birth counts remain unchanged from the original statistical sources.

## Results

The main findings are summarized in an interactive dashboard:
https://public.tableau.com/views/elements_17670363764070/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

The dashboard compares calendar-based and solar-ecliptic aggregations
across countries and years.

## Data sources
England and Wales https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/livebirths/articles/howpopularisyourbirthday/2015-12-18

Denmark
https://www.statbank.dk/

USA
https://thedailyviz.com/2016/09/17/how-common-is-your-birthday-dailyviz/

France
https://www.insee.fr/fr/statistiques/8582123?sommaire=8582147

Netherlands
https://opendata.cbs.nl/#/CBS/nl/dataset/70703ned/table?searchKeywords=keyword:geboorten

Malaysia
https://data.gov.my/data-catalogue/births?utm_source=chatgpt.com

Switzerland
https://www.bfs.admin.ch/bfs/en/home/statistics/population/births-deaths/births.assetdetail.35607811.html
