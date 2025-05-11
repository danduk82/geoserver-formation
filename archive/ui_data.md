---
marp: true
title: Daten & Layer-Verwaltung
---

# Layervorschau

Die **Layer-Vorschau** zeigt alle veröffentlichten Layer.

📌 Angezeigte Infos:
- Typ (Vektor, Raster, Gruppe, WMS)
- Interner Name & Titel
- Vorschau-Formate

> Nur „veröffentlichte“ Layer erscheinen im GetCapabilities-Dokument.

🌐 Format *OpenLayers* öffnet eine Live-Vorschau:

![OpenLayers Vorschau](../../assets/ui_layer_preview_openlayers.png)

---

# Arbeitsbereiche

Ein Arbeitsbereich bündelt:
- Datenquellen
- Gruppenlayer
- Styles

🔁 Empfohlene Reihenfolge:
1. Arbeitsbereich
2. Datenspeicher
3. Layer & Styles

📁 Beispiel-Arbeitsbereiche: `sf`, `topp`, `cite` …

🧪 Aufgabe:
- Arbeitsbereich `FOSSGIS` anlegen mit URI `http://geoserver.org/fossgis`

![Arbeitsbereiche](../../assets/ui_workspaces.png)

---

# Datenspeicher

Ein **Datastore** verbindet GeoServer mit der Quelle (DB, Datei, Dienst).

Beispiele:
- Shape-Datei (![](../../assets/ui_datastore_type_shape.png))
- PostGIS (![](../../assets/ui_datastore_type_db.png))
- WMS (![](../../assets/ui_datastore_type_wms.png))
- Raster (![](../../assets/ui_datastore_type_raster.png))

📌 Jeder Speicher gehört zu einem Workspace

![Datenspeicher](../../assets/ui_datastores.png)

---

# Layer & Gruppenlayer

Ein **Layer** zeigt Daten (Vektor/Raster) aus einem Speicher.

Ein **Gruppenlayer** kombiniert mehrere Layer.

📌 Jeder Layer gehört zu einem Speicher & Workspace  
📌 WMS/WFS werden automatisch mit jedem Layer generiert

Gruppenlayer-Ansicht:

![Gruppenlayer](../../assets/ui_layer_groups.png)

---

# Styles (SLD)

Styles definieren die Darstellung:

- Symbolisierung nach Attributen
- Mehrere Styles pro Layer möglich
- Über die GUI editierbar oder via Datei-Upload

![Style-Liste](../../assets/ui_styles.png)

✏️ Style-Editor bietet Validierung & Vorschau.
