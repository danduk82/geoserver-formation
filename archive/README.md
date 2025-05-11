---
marp: true
title: Einführung in GeoServer
---

![](./assets/geoserver-logo.png)

# Einführung in GeoServer

Willkommen zum **Einführung in GeoServer** Workshop.

Dieser Workshop wurde für [OSGeo-Live {{ book.osGeoLiveVersion }}](https://live.osgeo.org) entwickelt und bietet einen umfassenden Überblick über GeoServer als Web-Mapping-Lösung.


---

> ℹ️ **Information**  
> Der Workshop kann [als PDF](../{{ book.workshopPdfNameDe }}) heruntergeladen werden.

Bitte führen Sie zuerst die Schritte auf der Seite  
[Vorarbeiten und generelle Informationen](environment/README.md) aus,  
um einen reibungslosen Ablauf zu gewährleisten.


---

## Module im Workshop

* **Vorarbeiten und generelle Informationen**  
  OSGeoLive, Pfade, URLs, Zugangsdaten

* **Basiswissen GeoServer**  
  Einführung und Architektur

* **Administrationsoberfläche**  
  Konfiguration via Web-GUI

* **Datenveröffentlichung**  
  Vektor-/Rasterquellen, WFS/WMS

* **Gruppenlayer**  
  Kombinierte Layer als Einheit

* **Styling**  
  SLD-basierte Darstellung


---

## Autoren

{% for author in book.authors %}
- {{ author.name }} ([{{ author.mail }}](mailto:{{ author.mail }}))
{% endfor %}
