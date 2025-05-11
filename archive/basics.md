---
marp: true
title: Basiswissen GeoServer
---

# Was ist GeoServer?

[GeoServer](http://geoserver.org/) ist ein freier, Java-basierter Server  
zur Anzeige und Bearbeitung von Geodaten per OGC-Standards (z. B. WMS, WFS).

**Stärken:**  
- Offen & erweiterbar  
- Gut dokumentiert

📚 **Dokumentation**  
- Benutzer: [docs.geoserver.org/stable/en/user](https://docs.geoserver.org/stable/en/user)  
- Entwickler: [docs.geoserver.org/stable/en/developer](https://docs.geoserver.org/stable/en/developer)

---

## Installation & Versionen

- Offizielle `.war`-Datei: [geoserver.org/download](http://geoserver.org/download/)
- Deployment in Servlet-Container (Tomcat, Jetty)

📦 Alternativ:  
- Download bestimmter Versionen möglich  
- Siehe [https://geoserver.org/release/2.22.2/](https://geoserver.org/release/2.22.2/)

🛠️ Entwicklungszyklus:  
- 6 Monate, siehe [Roadmap](http://geoserver.org/roadmap/)

---

## GeoServer unter OSGeoLive

> ℹ️ **Bereits vorinstalliert!**  
> Aufrufbar unter: {{ book.geoServerBaseUrl }}

Unterschied zur klassischen Installation:  
- `start.jar` startet Jetty + GeoServer automatisch

Details siehe: [../environment/README.md](../environment/README.md)

---

## Nächster Schritt

Im nächsten Abschnitt [Administrationsoberfläche](../ui/index.html)  
sehen wir uns die Servereinstellungen, Logs und Sicherheitsaspekte an.
