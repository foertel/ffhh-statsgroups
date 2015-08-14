# ffcollectd
Konfiguration für die Gruppen in der Freifunk Statistik

## Format
Jede Datei in groups.regex beschreibt eine Gruppe. Der Dateiname entspricht dem Gruppennamen, die Datei README.md wird ignoriert.
Die erste Zeile in der Datei ist eine Regular Expression. Es wird nur die erste Zeile ausgewertet.

### Beispiel
Dateiname: Rote Flora

^Flora-Bleibt-Unvertraeglich-.*|^bb-flora-.*

Es wird ein Eintrag in der Statistik gebildet, mit den Namen " Gruppe: Rote Flora".
Alle Knoten deren Namen mit "Flora-Bleibt-Unvertraeglich-" oder "bb-flora-" beginnen,
werden in der Gruppe berücksichtigt.
