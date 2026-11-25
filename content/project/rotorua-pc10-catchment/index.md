---
title: Lake Rotorua PC10 Catchment Modelling
summary: A scoping study of coupled surface water-groundwater catchment modelling frameworks (SWAT+gwflow and SWAT-MODFLOW-RT3D) for three Lake Rotorua sub-catchments, to identify a platform capable of providing scenario-ready lake model inputs.
tags:
  - Catchment Modelling
  - Groundwater
  - Water Quality
  - Hydrology
  - Bay of Plenty Regional Council
date: '2026-11-01T00:00:00Z'
slug: rotorua-pc10-catchment

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: "The three pilot sub-catchments (Puarenga, Hamurana, Waingaehe) within the wider Lake Rotorua catchment, showing the mismatch between BOPRC's surface-water catchment delineation and GNS's groundwater sub-catchment delineation."
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

**Client:** Bay of Plenty Regional Council

Phase 1 of the Lake Rotorua integrated catchment modelling programme was a scoping study to identify a catchment modelling framework capable of providing scenario-ready lake model inputs under Plan Change 10 (PC10), which sets a Trophic Level Index target for Lake Rotorua requiring a sustainable nitrogen load of ~435 tN/yr.

Lake Rotorua's water quality is governed by slow-moving groundwater with transit times of decades to over a century, and roughly 45–60 km² of groundwater catchment extends beyond the surface-water topographic boundary. We reviewed candidate modelling platforms against five criteria — incongruous groundwater/surface-water boundaries, multi-decade concentration lags, surface water-groundwater interaction, chemistry at the lake edge, and response to changing land use and climate — and built minimal-complexity pilot models of three sub-catchments (Puarenga, Hamurana and Waingaehe) using the two most promising frameworks, SWAT+gwflow and the legacy SWAT2012-MODFLOW-RT3D coupling.

Both frameworks ran stably over a 44-year simulation period, but neither could fully meet the project's requirements: SWAT+gwflow's single unconfined groundwater layer cannot extend beyond the surface-water catchment or resolve multi-decade lags, while SWAT-MODFLOW-RT3D can represent a larger groundwater domain and multi-layer flow but lacks a working dynamic land-use workflow and was found to have reactive-transport bugs affecting nitrate and phosphorus output. Based on these findings, Phase 2 is redirected toward a bespoke, semi-distributed catchment model in the lineage of NIWA's ROTAN, built on groundwater catchments with tritium-calibrated transit-time distributions and time-varying land use.
