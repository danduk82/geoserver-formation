---
marp: true
title: Rasterdatenquellen
---

# GeoTIFF

GeoTIFF ist ein häufig verwendetes Rasterdatenformat (verlustfrei, georeferenziert).

🧪 **Aufgabe:**
1. Datenspeicher erstellen mit `data/sf/sfdem.tiff`
2. Stil: `dem` unter „Publishing → WMS Settings“
3. Vorschau öffnen

Das Beispiel zeigt ein digitales Höhenmodell aus South Dakota.

---

# ImageMosaic

Ein *ImageMosaic* erlaubt es, mehrere Rasterdaten als ein Mosaik zu veröffentlichen.

🧪 **Aufgabe:**
1. Datenspeicher mit `coverages/mosaic_sample` erstellen
2. Als Mosaik veröffentlichen
3. Layer-Vorschau ansehen

![Satelliten-Mosaik](../../assets/raster2.png)

---

# WMS (kaskadiert)

Ein externer WMS kann über GeoServer eingebunden und weiterverarbeitet werden.

🧪 **Aufgabe:**
1. WMS-Dienst wie  
   https://www.wms.nrw.de/geobasis/wms_nw_dgm-schummerung

2. Dienst kaskadieren und veröffentlichen
3. Vorschau öffnen

![DGM-Relief](../../assets/raster3.png)
