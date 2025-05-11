---
marp: true
title: Vektordatenquellen
---

# Shapefile

Shapefiles sind eines der am weitesten verbreiteten Vektorformate in der GIS-Welt.

🧪 **Aufgabe:**
1. Datenspeicher `us_states` anlegen, Datei `states.shp` aus `data_dir/data/shapefiles` verwenden
2. SRS: `EPSG:4326`, BoundingBox automatisch berechnen
3. Layer-Vorschau in OpenLayers öffnen

![Veröffentlichtes Shapefile](../../assets/vector1.png)

---

# PostGIS

PostGIS erweitert PostgreSQL um räumliche Funktionen (Abfragen, Bearbeitung).

🧪 **Aufgabe:**
1. Verbindung mit DB `natural_earth2`, User/Passwort: `user`
2. Tabelle veröffentlichen, SRS: `EPSG:54009`
3. Layer-Vorschau öffnen

Nutzen Sie SQL und Geometrien direkt aus der Datenbank!

---

# WFS

GeoServer kann externe Web Feature Services (WFS) als Quelle nutzen.

🧪 **Aufgabe:**
1. WFS-Dienst kaskadieren, z. B.  
   https://www.wfs.nrw.de/geobasis/wfs_nw_dvg?...

2. Dienst veröffentlichen und in OpenLayers ansehen

> 💡 Falls kein Style erkannt wird:  
> Im Reiter *Publishing* → Style auf *Polygon*, *Point* oder *Line* setzen
