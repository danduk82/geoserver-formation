---
marp: true
title: Serverstatus & Protokolle
---

# Serverstatus

Unter **Serverstatus** finden Sie Infos zum Zustand des Kartenservers:

- Java-Version, Speicherverbrauch
- Verwendetes Datenverzeichnis
- Schriftarten, Umgebung

🛠️ Nützlich bei:
- Performanceproblemen
- Änderungen im Dateisystem

🔁 **Aktionen:**
- Konfiguration neu laden
- Cache leeren
- Speicher freigeben

![Statusansicht](../../assets/ui_server_status.png)

---

# Protokollierung

Bei GeoServer-Fehlern ➜ **Log prüfen**

🔍 Zugriff:
- über Web-GUI  
- oder Datei: `{{ book.geoServerPhysicalPath }}logs/geoserver.log`

✏️ Konfigurierbar:
- Anzahl Zeilen
- Protokoll-Level (z. B. ERROR)

Beispiel:
```
ERROR [geoserver.wms] - ... does not have a properly configured datastore
```

➡️ Siehe auch [Einstellungen](../settings/README.md)

![Log-Ansicht](../../assets/ui_logs.png)

---

# Kontaktinformationen

Diese Angaben erscheinen im **GetCapabilities**-Dokument.

🧪 **Aufgabe:**
1. Öffnen Sie WMS → 1.3.0 → GetCapabilities
2. Fügen Sie Ihre Kontaktdaten hinzu
3. Aktualisieren Sie die Capabilities — Was hat sich verändert?

![Kontaktformular](../../assets/ui_contact_information.png)
