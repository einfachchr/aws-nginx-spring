# von diesem Image starten wir (vanilla nginx)
FROM nginx:latest


# lokale Config-Daten in den Container kopieren
#   Wichtig: auf das richtige Verzeichnis achten!
COPY nginx.conf /etc/nginx/


# Port 80 nach außen veröffentlichen
EXPOSE 80


# führt das Kommando 'nginx -g "daemon off";' aus
#     -g      global configuration directives
#     daemon  Determines whether nginx should become a daemon. 
#             Der Aufruf muss blocken, sonst weiss der Container 
#             nicht, ob der Prozess noch läuft.
CMD nginx -g "daemon off;"
