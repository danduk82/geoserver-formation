---
marp: true
title: GeoServer Dienste (WFS / WMS)
---

# Web Feature Service (WFS)

Globale Einstellungen für WFS-Dienste:

- 📝 **Metadaten** → erscheinen im GetCapabilities
- 🔐 Checkbox *WFS aktiv* muss aktiviert sein
- 🔢 *Maximale Anzahl Features* einstellbar

⚙️ **Dienstgüte:**
- `Basis`: nur Lesen (GetCapabilities, GetFeature)
- `Transaktional`: + CREATE / UPDATE / DELETE (WFS-T)
- `Vollständig`: + LockFeature zum Sperren von Features

👉 Details: [GeoServer-Doku](https://docs.geoserver.org/stable/en/user/services/wfs/webadmin.html#service-metadata)

---

# Web Map Service (WMS)

Globale Einstellungen für WMS-Dienste:

- 📝 **Metadaten** → erscheinen im GetCapabilities
- 🌍 CRS-Liste kann eingeschränkt werden (z.B. `4326, 25833`)
- 🎨 **Raster-Rendering**: Nächster Nachbar (Standard), Bilinear, Bicubic
- 🖼️ **Wasserzeichen**: aktivierbar, erscheint pro Kachel
- 💾 **PNG/JPEG-Kompression**: 0–100 (%), Standard: `25`

👉 Details: [GeoServer-Doku](https://docs.geoserver.org/stable/en/user/services/wms/webadmin.html#service-metadata)
