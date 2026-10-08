# Hitster België – technische test

Publiceer `index.html` en `songs.json` in de hoofdmap van een publieke GitHub Pages repository. Kies Settings > Pages > Deploy from a branch > main / (root).

Voeg in het Spotify Developer Dashboard bij Redirect URIs de exacte GitHub Pages URL toe, inclusief afsluitende `/`, bijvoorbeeld `https://GEBRUIKERSNAAM.github.io/hitster-belgie/`. De code gebruikt automatisch de URL van de gepubliceerde pagina. Open de app uitsluitend via HTTPS.

De QR-code opent de app met `?play=demo-1`. De scannende telefoon moet afzonderlijk Spotify autoriseren; dit is geen garantie voor automatisch afspelen. Spotify kan beperkingen opleggen aan development-mode apps en playback API's. Er moet een afspeelbaar Spotify Connect-toestel zijn.

De vijf nummers zijn **niet geverifieerde voorbeelden**, zonder Spotify-track-ID's. Voeg alleen exacte Spotify track-ID's van 22 tekens toe nadat de opname is gecontroleerd. `songs.json` is bedoeld als startpunt voor een gecontroleerde collectie; weekaantallen zijn nog niet gevalideerd. Geen Client Secret nodig (PKCE).
