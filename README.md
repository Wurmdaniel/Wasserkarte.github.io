Ein Versuche eine nachhaltige digitale Infrastruktur zu schaffen

Die Idee:
Sensordaten werden auf der opensensemap gespeichert und per API Abfrage direkt in eine leaflet eingefügt - es bedarf keinen eignen Server!
Wir nutzen dazu den Grouptag "Flaeming" um nach Daten aus dem Bodenfeuchtesensorennetzwerk zu filtern.

Get DATA from the OSM
-> https://api.opensensemap.org/
-> https://docs.opensensemap.org/#api-Measurements-getDataByGroupTag


API Abfrage Sensebox nach Grouptag/Sensebox/Sensor
https://api.opensensemap.org/boxes/data/bytag?grouptag=Flaeming
https://api.opensensemap.org/boxes/631100372977aa001c351492
https://api.opensensemap.org/boxes/631100372977aa001c351492/sensors/638f1beb73c881001cbcc114
