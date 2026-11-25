---
title: "WaterFootprint C3"
summary: An R Shiny application that estimates contaminant loads, mitigation costs and carbon emissions for land use change scenarios across the Auckland region.
tags:
  - Water Quality
  - Water Management
  - Land Use
  - Carbon Emissions
  - Auckland Council
date: '2025-08-01T00:00:00Z'
slug: water-footprint

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

**Client:** Auckland Council

Limnotrack developed the WaterFootprint C3 Shiny application for Auckland Council, translating the WaterFootprint C3 Excel calculator (Contaminant :: Cost :: Carbon) into a group of R functions wrapped in an interactive web app. For any user-selected area of interest in the Auckland region (up to ~27,850 ha), the app:

- Loads the most recent land cover classification and allows users to model future land use change scenarios
- Estimates contaminant loads for total suspended solids (TSS), total zinc (TZn), total copper (TCu), total phosphorus (TP) and total nitrogen (TN)
- Simulates stormwater mitigation options at the source and sub-catchment scale
- Estimates the capital and ongoing costs of those mitigations
- Calculates life-cycle carbon emissions associated with each scenario
- Supports side-by-side comparison of scenarios and exports results as a formatted PDF report

The tool gives Auckland Council staff a consistent, spatial way to evaluate the water quality, cost and carbon trade-offs of land use and stormwater mitigation decisions across the region.
