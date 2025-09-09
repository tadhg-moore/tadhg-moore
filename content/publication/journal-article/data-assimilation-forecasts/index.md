---
title: "Near-term forecasts of NEON lakes reveal gradients of environmental predictability across the U.S."
authors:
- Heather L. Wander
- R. Quinn Thomas
- Tadhg Moore
- Mary E. Lofton
- Adrienne Breef-Pilz
- Cayelan C. Carey

date: "2024-02-13T00:00:00Z"
doi: "10.1002/ecs2.4752"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Ecosphere"
publication_short: ""

abstract: Ecosystems around the globe are experiencing changes in both the magnitude and fluctuations of environmental conditions due to land use and climate change. In response, ecologists are increasingly using near-term, iterative ecological forecasts to predict how ecosystems will change in the future. To date, many near-term, iterative forecasting systems have been developed using high temporal frequency (minute to hourly resolution) data streams for assimilation. However, this approach may be cost-prohibitive or impossible for forecasting ecological variables that lack high-frequency sensors or have high data latency (i.e., a delay before data are available for modeling after collection). To explore the effects of data assimilation frequency on forecast skill, we developed water temperature forecasts for a eutrophic drinking water reservoir and conducted data assimilation experiments by selectively withholding observations to examine the effect of data availability on forecast accuracy. We used in situ sensors, manually collected data, and a calibrated water quality ecosystem model driven by forecasted weather data to generate future water temperature forecasts using Forecasting Lake and Reservoir Ecosystems (FLARE), an open source water quality forecasting system. We tested the effect of daily, weekly, fortnightly, and monthly data assimilation on the skill of 1- to 35-day-ahead water temperature forecasts. We found that forecast skill varied depending on the season, forecast horizon, depth, and data assimilation frequency, but overall forecast performance was high, with a mean 1-day-ahead forecast root mean square error (RMSE) of 0.81°C, mean 7-day RMSE of 1.15°C, and mean 35-day RMSE of 1.94°C. Aggregated across the year, daily data assimilation yielded the most skillful forecasts at 1- to 7-day-ahead horizons, but weekly data assimilation resulted in the most skillful forecasts at 8- to 35-day-ahead horizons. Within a year, forecasts with weekly data assimilation consistently outperformed forecasts with daily data assimilation after the 8-day forecast horizon during mixed spring/autumn periods and 5- to 14-day-ahead horizons during the summer-stratified period, depending on depth. Our results suggest that lower frequency data (i.e., weekly) may be adequate for developing accurate forecasts in some applications, further enabling the development of forecasts broadly across ecosystems and ecological variables without high-frequency sensor data.

# Summary. An optional shortened abstract.
summary:  To date, many near-term, iterative forecasting systems have been developed using high temporal frequency (minute to hourly resolution) data streams for assimilation. We developed water temperature forecasts for a eutrophic drinking water reservoir and conducted data assimilation experiments by selectively withholding observations to examine the effect of data availability on forecast accuracy. Our results suggest that lower frequency data (i.e., weekly) may be adequate for developing accurate forecasts in some applications, further enabling the development of forecasts broadly across ecosystems and ecological variables without high-frequency sensor data.

tags:
- FLARE
- Ecological Forecasting
- Lake Modelling
- Uncertainty
- High-frequency sensors

featured: false

links:
url_pdf: https://esajournals.onlinelibrary.wiley.com/doi/epdf/10.1002/ecs2.4752
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
  caption: 'Forecasting Lake And Reservoir Ecosystems workflow showing the step-by-step process for generating daily water temperature forecasts, starting with data collection from thermistors deployed in the reservoir (step 1), then data access for running the forecast model (step 2), then generation of forecasts with data assimilation (step 3), and ending with forecast skill assessment (step 4). During the data assimilation steps (3a–b), data assimilation experiments were performed with four different data assimilation frequencies (daily, weekly, fortnightly, and monthly; see dashed line box).'
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

