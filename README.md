# Co.Citation — Reference Co‑Citation Map (Supplementary Materials)

This repository provides the **reference co‑citation map** used in the paper *“Music Events & Tourism: insights from a scoping review and bibliometric performance analysis (2000–2024)”*.

## Contents
- `settings/vosviewer_settings.md` — exact VOSviewer parameters (counting = full; min cites = 6; normalization = association strength; clustering: resolution = 1.0; min cluster = 5).
- `thesaurus/thesaurus_light.txt` — light label harmonization (e.g., `& → and`, punctuation).
- `maps/cocitation.png` — high‑resolution map exported from VOSviewer (manuscript‑ready).
- `provenance/export_notes.txt` — input source, freeze/search dates, and export notes.

## Freeze date & scope
- **Corpus**: Scopus export of the 232 screened articles (years 2000–2024; English; journal articles; final stage).
- **Search date**: 10 July 2025.
- **Citation freeze**: 10 July 2025. **CPY reference year**: 2025.

## How this map was generated
Open VOSviewer 1.6.20 → *Create* → *Map based on bibliographic data* → **Scopus** → *Co‑citation* (Unit = *Cited references*). Apply the settings in `settings/vosviewer_settings.md`, load the thesaurus at `thesaurus/thesaurus_light.txt`, and export the figure as `maps/cocitation.png` (≥1200 px).

## Reproduce
1. Obtain the cleaned dataset (Scopus export) from the code+data repository:  
   https://github.com/tuannguyencntt2712-hub/music-events-tourism-bibliometrix
2. Follow `settings/vosviewer_settings.md` and the steps above to regenerate the map.

## Notes
- VOSviewer layouts are stochastic; minor visual differences can occur across runs.
- The figure `maps/cocitation.png` has not been edited post‑export.

## Citation
Please cite this repository as:
> Thanh Tuan, N., & Le Anh, T. (2025d). *Co.Citation* [Supplementary materials]. GitHub. https://github.com/tuannguyencntt2712-hub/Co.Citation
