---
layout: archive
title: "Technical Portfolio"
permalink: /
author_profile: true
# redirect_from: 
#   - /about/
#   - /about.html
---

*A selection of geospatial research, field-based data modeling from my tenure at Cal Poly Humboldt, focusing on endangered species conservation and remote sensing workflows.*

---
# Raster File Analysis
## Spatial Ecology of Giant Kangaroo Rats (Carrizo Plain)
I supported a multi-year population study of the endangered **Giant Kangaroo Rat (Dipodomys ingens)**. My primary contribution involved high-precision **digitization and annotation** of GKR burrow systems to track population density and spatial distribution using **[NAIP Imagery](https://storymaps.arcgis.com/stories/2da7f6d7bd2d4555b474c6057f4abcc8)**.

### Research Context: GIS & Remote Sensing Analysis
*The following StoryMap by Kira Dowdakin illustrates the broader research context and how the digitized plot and burrow data (see "Plot and Burrow Data" section) inform spatial conservation models.*

<div class="storymap-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border: 1px solid #ddd;">
  <iframe 
    src="https://storymaps.arcgis.com/stories/2da7f6d7bd2d4555b474c6057f4abcc8" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
    frameborder="0" 
    allowfullscreen 
    allow="geolocation">
  </iframe>
</div>

---

## 🔥 Normalized Burn Ratio Analysis: 2014 Lassics Wildfires
**Project Focus:** Remote Sensing & Fire Ecology

This technical report evaluated the impact of the **Mad River and Humboldt Lightning Complex fires** on the habitat of the endangered **Lassics lupine** (*Lupinus constancei*). The project involved multi-temporal satellite data processing to classify burn severity.

### Technical Methodology:
* **Image Pre-processing:** Conducted **Radiometric Calibration** and **Dark Subtraction** on Level 1 Landsat 8 datasets to ensure scientific consistency.
* **Spectral Analysis:** Calculated the **Difference Normalized Burn Ratio (dNBR)** to identify landscape changes and classify burn severity into six categories (from "New Growth" to "High Severity").
* **Data Synthesis:** Classified approximately **215 hectares** of the study area to provide a baseline for erosion risk and lupine population monitoring.

### 🛰️ Analysis Gallery
*A step-by-step visualization of the dNBR (Normalized Burn Ratio) workflow.*

<style>
  .slider { width: 100%; text-align: center; overflow: hidden; position: relative; border: 1px solid #ddd; border-radius: 8px; }
  .slides { display: flex; overflow-x: auto; scroll-snap-type: x mandatory; scroll-behavior: smooth; -webkit-overflow-scrolling: touch; }
  .slides::-webkit-scrollbar { height: 10px; }
  .slides::-webkit-scrollbar-thumb { background: #f48b3c; border-radius: 10px; }
  .slides > div { scroll-snap-align: start; flex-shrink: 0; width: 100%; height: 450px; margin-right: 2px; display: flex; justify-content: center; align-items: center; background: #eee; position: relative; }
  .slides img { max-width: 100%; max-height: 100%; object-fit: contain; }
  .slide-label { position: absolute; bottom: 10px; background: rgba(0,0,0,0.6); color: white; padding: 5px 15px; border-radius: 20px; font-size: 0.8em; }
</style>

<div class="slider">
  <div class="slides">
    <div id="slide-1"><img src="/images/lassics-1.png"><span class="slide-label">Aerial Overlay</span></div>
    <div id="slide-2"><img src="/images/lassics-2.png"><span class="slide-label">Pre-Fire (2014)</span></div>
    <div id="slide-3"><img src="/images/lassics-3.png"><span class="slide-label">Post-Fire (2015)</span></div>
    <div id="slide-4"><img src="/images/lassics-4.png"><span class="slide-label">Pre-Fire NBR</span></div>
    <div id="slide-5"><img src="/images/lassics-5.png"><span class="slide-label">Post-Fire NBR</span></div>
    <div id="slide-6"><img src="/images/lassics-6.png"><span class="slide-label">Final dNBR</span></div>
  </div>
</div>
<p style="text-align: center;"><i>← Scroll or swipe to view all 6 analysis maps →</i></p>
---