---
title: "Data assimilation experiments inform monitoring needs for near-term ecological forecasts in a eutrophic reservoir"
authors:
- Heather L. Wander
- R. Quinn Thomas
- Tadhg Moore
- Mary E. Lofton
- Adrienne Breef-Pilz
- Cayelan C. Carey

date: "2023-05-23T00:00:00Z"
doi: "10.22541/essoar.168500255.59108131/v1"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Earth and Space Science Open Archive"
publication_short: ""

abstract: Ecosystems around the globe are experiencing increased variability due to land use and climate change. In response, ecologists are increasingly using near-term, iterative ecological forecasts to predict how ecosystems will change in the future. To date, many near-term, iterative forecasting systems have been developed using high temporal frequency (minute to hourly resolution) data streams for assimilation. However, this approach may be cost-prohibitive or impossible for forecasting ecological variables that lack high-frequency sensors or have high data latency (i.e., a delay before data are available for modeling after collection). To explore the effects of data assimilation frequency on forecast skill, we developed water temperature forecasts for a eutrophic drinking water reservoir and conducted data assimilation experiments by selectively withholding observations to examine the effect of data availability on forecast accuracy. We used  in-situ sensors, manually collected data, and a calibrated water quality ecosystem model driven by forecasted weather data to generate future water temperature forecasts using FLARE (Forecasting Lake And Reservoir Ecosystems), an open-source water quality forecasting system. We tested the effect of daily, weekly, fortnightly, and monthly data assimilation on the skill of 1 to 35-day-ahead water temperature forecasts. We found that forecast skill varied depending on the season, forecast horizon, depth, and data assimilation frequency, but overall forecast performance was high, with a mean 1-day-ahead forecast root mean square error (RMSE) of 0.94°C, mean 7-day RMSE of 1.33°C, and mean 35-day RMSE of 2.15°C. Aggregated across the year, daily data assimilation yielded the most skillful forecasts at 1-7-day-ahead horizons, weekly data assimilation resulted in the most skillful forecasts at 8-35-day-ahead horizons. Within a year, daily to fortnightly data assimilation substantially outperformed monthly data assimilation in the stratified summer period, whereas all data assimilation frequencies resulted in skillful forecasts across depths in the mixed spring/autumn periods for shorter forecast horizons. Our results suggest that lower-frequency data (i.e., weekly) may be adequate for developing accurate forecasts in some applications, further enabling the development of forecasts broadly across ecosystems and ecological variables without high-frequency sensor data. 

# Summary. An optional shortened abstract.
summary: This study examines how the frequency of data assimilation affects the accuracy of near-term ecological forecasts, specifically for water temperature in a eutrophic reservoir. Using the FLARE forecasting system, researchers tested daily, weekly, fortnightly, and monthly data assimilation to predict water temperature 1 to 35 days ahead. They found that daily assimilation produced the most accurate short-term forecasts (1–7 days), while weekly assimilation performed best for longer-term predictions (8–35 days). Seasonal and depth variations influenced forecast accuracy, with higher-frequency assimilation being especially important during summer stratification. The findings suggest that even lower-frequency data (e.g., weekly) can yield skillful forecasts, broadening forecasting applications beyond ecosystems with high-frequency sensors.

tags:
- Ecological Forecasting
- Lake Modelling
- Sensor data
- Uncertainty

featured: false

links:
- name: Pre-print
  url: https://essopenarchive.org/doi/full/10.22541/essoar.168500255.59108131
url_pdf: https://essopenarchive.org/doi/full/10.22541/essoar.168500255.59108131
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Forecasting Lake And Reservoir Ecosystems (FLARE) workflow showing the step-by-step process for generating daily water temperature forecasts, starting with data collection from thermistors deployed in the reservoir (step 1), then data access for running the forecast model   (step 2), then generation of forecasts with data assimilation (step 3), and ending with forecast skill assessment (step 4).'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- flare

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

