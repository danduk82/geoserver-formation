---
marp: true
title: Globale Einstellungen & Sicherheit
---

# Globale Einstellungen

🛠️ Optionen unter „Globale Einstellungen“:

- `Ausführliche Meldungen`: XML-Ausgaben formatiert (nur für Tests)
- `Zeichensatz`: Standard ist UTF-8 → nicht ändern
- `Proxy URL`: Nur bei Einsatz hinter Reverse Proxy (z. B. Apache)
- `Speicherort für Protokolle`: Standard `logs/geoserver.log`

📋 **Logging-Profile:**
- `DEFAULT_LOGGING`: Mittel (Standard)
- `PRODUCTION_LOGGING`: Nur Fehler (für Betrieb)
- `GEOSERVER_DEVELOPER_LOGGING`: Für Debugging GeoServer
- `GEOTOOLS_DEVELOPER_LOGGING`: Für Debugging SQL/GeoTools
- `VERBOSE_LOGGING`: Max. Ausführlichkeit

---

# Sicherheit

🔐 In diesem Menü konfigurieren Sie:

- Benutzer und Passwörter
- Rechtevergabe
- Zugriffsbeschränkungen für Datenspeicher

🧪 **Aufgabe:**
1. Ändern Sie das Standardpasswort des Benutzers `admin`  
   von `geoserver` auf ein eigenes Passwort
