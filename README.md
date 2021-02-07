# DD Movebis
Aufbereitung und Darstellung der Radverkehrsdaten aus dem Movebis-Projekt [1].

Im Rahmen von "Stadtradeln" hat das Movebis-Projekt deutschlandweit GPS-Tracks von teilnehmenden Radfahrer'innen gesammelt. Anzahl Beobachtungen und durchschnittliche Geschwindigkeiten sind OSM-Links zugefügt worden und können nun auf mcloud [2] heruntergeladen werden.

Dieses Projekt basiert auf https://github.com/vizsim/movebis Vielen Dank für diese Inspiration.

## Anforderungen

### Movebis-Daten

Auf mcloud [2] befinden sich 3 Datensätze aus dem Movebis-Projekt: Radverkehrsmengenkarte [3], Geschwindigkeiten der Radfahrenden [4] und Heatmap Radverkehr [5]. Die Daten sollten entpackt unter '''data\movebis''' abgelegt werden.

Diese Daten sind unter Creative Commons Namensnennung - Nicht kommerziell (CC BY-NC) lizenziert.

### Shapefile für sächsische Gemeindegrenzen

Beim Staatsbetrieb Geobasisinformation und Vermessung Sachsen gibt es die Verwaltungsgrenzen als Shapefiles. Diese Daten sind entpackt unter '''data\shapefiles''' abzulegen.

### Python-Bibliotheken

Das Projekt läuft aktuell mit Python 3.8.0 und benötigt die folgenden Bibliotheken: pandas, geopandas, numpy, shapely, matplotlib, contextily, folium, branca (und ggf. requests, requests-cache)



Quellen:

[1] https://www.movebis.org/
[2] https://www.mcloud.de/web/guest/suche/-/results/suche/relevance/movebis/0
[3] https://www.mcloud.de/web/guest/suche/-/results/suche/relevance/movebis/0/detail/ECF9DF02-37DC-4268-B017-A7C2CF302006
[4] https://www.mcloud.de/web/guest/suche/-/results/suche/relevance/movebis/0/detail/33427A5A-0ADB-40B1-8A1A-390B67B0380B
[5] https://www.mcloud.de/web/guest/suche/-/results/suche/relevance/movebis/0/detail/3096DB7A-9EE4-4C14-B2AA-79E33A7FFF01
[6] https://www.geodaten.sachsen.de/downloadbereich-verwaltungsgrenzen-4344.html