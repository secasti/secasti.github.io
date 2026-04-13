---
layout: archive
title: "Portfolio"
permalink: /
author_profile: true

---

# Spatial Modeling
## Ecological Niche Modeling: Species Distribution & Climate Projections for the American Bullfrog (*Rana catesbeiana*) 
Using Maxent (Maximum Entropy) modeling and the Warren and Seifert (2012) likelihood calculation, I identified an optimal niche model based on parsimonious bioclimatic variables and a \Delta AICc = 0 selection criterion. I analyzed the specific response curves for annual temperature and precipitation extremes to define the target species' environmental tolerances and establish a high-accuracy spatial baseline. By projecting these requirements 50 years into the future using an RCP 8.5 high-emissions scenario and the AC global climate model, I quantified potential shifts in habitat suitability. Results were shared with the local Forest Service office to support management efforts.

![RACA projected suitable habitat](/images/future_projection.jpg)

---
# Remote Sensing
## Spatial Ecology of Giant Kangaroo Rats (Carrizo Plain)
I supported a multi-year population study of the endangered **Giant Kangaroo Rat (*Dipodomys ingens*)**. My primary contribution involved high-precision **digitization and annotation** of GKR burrow systems to track population density and spatial distribution using **[NAIP Imagery](https://storymaps.arcgis.com/stories/2da7f6d7bd2d4555b474c6057f4abcc8)**.
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

## Fire Ecology in the Lassics
I evaluated the impact of the **Mad River and Humboldt Lightning Complex fires** on the habitat of the endangered **Lassics lupine** (*Lupinus constancei*). The project involved multi-temporal satellite data processing to classify burn severity. Image preprocessing included **Radiometric Calibration** and **Dark Subtraction** on Landsat statellite imagery. **Difference Normalized Burn Ratio (dNBR)** was conducted on approximately approximately **215 hectares** of the study area to classify burn severity and provide a baseline for erosion risk and lupine population monitoring.

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
## Mt. St. Helens: 45-Year Multi-Spectral Change Detection

In this multi-temporal remote sensing study, I performed a comparative analysis of Landsat Level-1 imagery to quantify landscape recovery following the 1980 eruption of Mt. St. Helens. Using ENVI, I conducted radiometric calibration and atmospheric correction on Landsat 3 MSS (1980) and Landsat 8 OLI/TIRS (2025) datasets to ensure spectral consistency across disparate sensor generations. I developed a standardized Region of Interest (ROI) to subset both scenes to an identical geographic extent, allowing for a high-precision visual and spectral assessment of vegetation re-colonization. By generating Near-Infrared (NIR) false-color composites and utilizing link-scaled map frames in ArcGIS Pro, I mapped the long-term successional changes in the blast zone and Spirit Lake watershed.

![Mt. St. Helens](/images/helens.png)

---
# Cartography

## Pacific Fisher (*Pekania pennanti*) Infographic
![Pacific fisher infographic](/images/fisher_infographic.jpg)

## Jeffrey Pine and Serpentine Soil Distributions
![Jeffrey Pine and Serpentine Soil Distributions](/images/serpentine_occurance.jpg)