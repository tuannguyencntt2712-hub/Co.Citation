# VOSviewer settings — Reference Co‑Citation (RCCA)

**Tool & version**: VOSviewer 1.6.20  
**Map type**: Map based on bibliographic data → *Scopus*  
**Unit of analysis**: *Cited references*  
**Counting method**: *Full counting*  
**Normalization**: *Association strength*  
**Inclusion threshold**: *Minimum number of citations of a cited reference = 6*  
**Clustering**: *Resolution = 1.0; Minimum cluster size = 5*  
**Label harmonization**: *Use thesaurus file* → `../thesaurus/thesaurus_light.txt`

---

## Why these settings?
- **Full counting** keeps each co‑citation link at full weight, which is standard for reference co‑citation in small/medium corpora.
- **Min citations = 6** yields a readable map while retaining influential references; lower thresholds over‑densify nodes.
- **Association‑strength normalization** is VOSviewer’s default and supports stable cluster separation.
- **Resolution = 1.0** and **min cluster size = 5** balance detail and readability; raise resolution (>1.0) only if clusters look overly broad.

---

## Step‑by‑step (reproducible procedure)
1. **Open** VOSviewer 1.6.20 → *Create* → **Map based on bibliographic data**.  
2. **Select data source**: *Scopus* → choose the Scopus export used for the paper (see provenance).  
3. **Type of analysis**: *Co‑citation* → **Unit**: *Cited references*.  
4. **Counting method**: *Full counting*.  
5. **Threshold**: set **Minimum number of citations of a cited reference = 6**.  
6. **Select items**: *Include all items that meet the threshold* (unless you have a specific filter).  
7. **Thesaurus** (optional but recommended): tick *Use a thesaurus file* → select `../thesaurus/thesaurus_light.txt`.  
8. **Normalization**: ensure *Association strength* is applied (default).  
9. **Clustering**: Resolution **1.0**; Minimum cluster size **5**.  
10. **Finish** to generate the map.  


---

## Thesaurus file (light)
Use `../thesaurus/thesaurus_light.txt` to normalize common label variants. 
> Format: `label;replace_by` (UTF‑8, no BOM). Add rows as needed to merge punctuation variants consistently.

---

## Provenance (fill in when exporting)
- **Freeze date for citation indicators**: 10 July 2025 (CPY ref year = 2025)  
- **Input export file**: (e.g.) `scopus_clean.csv` from repo *music-events-tourism-bibliometrix* (2025c)  
- **Map created on (UTC)**: 2025-09-17 13:07:12Z  
- **Links**: Code & queries → https://github.com/tuannguyencntt2712-hub/music-events-tourism-bibliometrix

---


