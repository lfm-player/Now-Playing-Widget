
# laut.fm Now Playing Widget

Mit dem kostenlosen laut.fm Now Playing Widget kannst du deinen Radiosender ganz einfach auf deiner eigenen Homepage präsentieren.

Das Widget zeigt automatisch, welcher Sender gerade läuft, welcher Interpret zu hören ist und wie der aktuelle Musiktitel heißt. Dazu wird das passende Künstlerbild oder – falls keines verfügbar ist – das Senderlogo angezeigt.

**Kostenlos, unkompliziert und ohne eigene technische Infrastruktur.**

Das Widget spielt selbst keine Musik ab. Die Wiedergabe erfolgt über den Universal laut.fm Webplayer.

🌐 **Live ausprobieren:**  
https://lfm-player.github.io/Now-Playing-Widget/

Die Verwendung erfolgt auf eigene Gefahr!

## ✨ So funktioniert es

1. Öffne das Widget.
2. Gib den Namen deines laut.fm-Senders ein, zum Beispiel `eins`.
3. Das Widget lädt automatisch deine Senderinformationen und den aktuell gespielten Titel.
4. Über **„Im Webplayer hören“** können deine Besucher deinen Sender direkt im Universal laut.fm Webplayer anhören.

## 🚀 Für deine Homepage

Wenn du das Widget für deinen eigenen Radiosender einbauen möchtest, kannst du den Stationsnamen direkt in der URL hinterlegen.

Beispiel für den Sender eins:

```html
<iframe
  src="https://lfm-player.github.io/Now-Playing-Widget/?station=eins&amp;accent=3988ff&amp;bg=10233d&amp;text=f4f8ff"
  width="100%"
  height="150"
  style="display:block;border:0;background:transparent;max-width:100%;"
  allowtransparency="true"
  scrolling="no"
  loading="lazy"
  title="laut.fm Now Playing Widget">
</iframe>
```

Ersetze `eins` einfach durch den Namen deines eigenen laut.fm-Senders.

Tipp: Passe bei Bedarf die Höhe (`height`) und die maximale Breite (`max-width`) an das Design deiner Homepage an.

## 🚀 Das bietet dir das Widget

- Anzeige deines laut.fm-Sendernamens
- Aktueller Interpret und Musiktitel
- Künstlerbild oder Senderlogo
- Automatische Aktualisierung alle 15 Sekunden
- Direkter Zugang zum Universal laut.fm Webplayer
- Modernes, responsives Design für PC, Tablet und Smartphone
- Einfache Einbindung über HTML-iframe

## 📡 Datenquellen

Die Senderinformationen und Musiktitel werden über die offizielle laut.fm-API abgerufen.

API-Endpunkte:

- Stationsinformationen: `https://api.laut.fm/station/{station}`
- Aktueller Titel: `https://api.laut.fm/station/{station}/current_song`
- Cover-Anzeige: `https://api.laut.fm/station/{station}/cover`

Die Audiowiedergabe erfolgt über den jeweiligen laut.fm-Stream.

## 🔧 Verwendete Technologien

- HTML5
- CSS3
- JavaScript
- laut.fm API
- laut.fm Audio-Streaming
- GitHub Pages
- Universal laut.fm Webplayer

Nach einem Klick auf **„Im Webplayer öffnen“** öffnet sich der externe Universal laut.fm Webplayer.

Das Widget benötigt keine eigene Datenbank und kein PHP-Backend.

## 🌍 Hosting

Das Now Playing Widget wird über **GitHub Pages** bereitgestellt.

Das Projekt ist als statische Website umgesetzt und benötigt keinen eigenen Webserver mit serverseitiger Programmlogik.

## 🔒 Datenschutz – Hinweis für Webseitenbetreiber

Wenn du das laut.fm Now Playing Widget über einen HTML-iframe in deine eigene Webseite einbindest, solltest du dies in deiner Datenschutzerklärung berücksichtigen.

Beim Aufruf des Widgets wird eine Verbindung zu GitHub Pages hergestellt. Zur Anzeige der aktuellen Musikinformationen erfolgen außerdem Anfragen an die laut.fm-API. Je nach Verfügbarkeit und Einbindung können auch externe Bildserver kontaktiert werden.

Dabei können insbesondere folgende technische Daten übertragen werden:

- IP-Adresse des Besuchers
- Datum und Uhrzeit der Anfrage
- Browser- und Geräteinformationen
- Technische Verbindungsdaten

Das Widget selbst verfügt über keine eigenen Tracking- oder Analysefunktionen und setzt nach der vorgesehenen Implementierung keine eigenen Tracking-Cookies.

**Empfehlung:** Informiere deine Besucher in deiner Datenschutzerklärung über die Einbindung des Widgets und die damit verbundenen externen Datenverbindungen. Prüfe außerdem, ob für deine konkrete Einbindung eine vorherige Einwilligung erforderlich ist.

Weitere Informationen:

- GitHub Datenschutzhinweise: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement
- laut.fm Datenschutz: https://laut.fm/datenschutz

## 📄 Lizenz und Hinweise

Dieses Projekt ist ein unabhängiges Now Playing Widget zur Anzeige von Informationen über laut.fm-Radiosendern.

laut.fm ist eine eigenständige Plattform. Markenrechte und Rechte an den bereitgestellten Inhalten verbleiben bei den jeweiligen Rechteinhabern.

Die Verfügbarkeit der Senderinformationen, Coverbilder und Audiostreams hängt von laut.fm und den jeweiligen Datenquellen ab.

## 🔒 Datenschutzhinweise

Dieses Projekt verwendet die öffentliche laut.fm-API, um Informationen zum Sendeplan und zum ausgewählten Radiosender abzurufen.

Beim Zugriff auf die laut.fm-API können technische Informationen an laut.fm übertragen werden. Dazu können insbesondere die IP-Adresse, Informationen zum verwendeten Webbrowser, das Betriebssystem und weitere technische Daten gehören.

Diese Datenübertragung erfolgt im Rahmen der technischen Nutzung der laut.fm-API.

Weitere Informationen zur Verarbeitung personenbezogener Daten findest du in der Datenschutzerklärung und Impressum von laut.fm.

Datenschutzerklärung und Impressum von laut.fm: https://laut.fm/pages/privacy

Weitere Informationen zur laut.fm-API: https://docs.api.laut.fm/

## ⚖️ Rechtliche Hinweise

Dieses Projekt ist ein eigenständiges, nicht kommerzielles Hobbyprojekt und wird unabhängig unter dem Namen **lfm-player** entwickelt und bereitgestellt.

Es besteht keine offizielle Verbindung, Partnerschaft oder Zusammenarbeit mit laut.fm, LAUT AG oder GitHub. Das Projekt wird von diesen Unternehmen weder unterstützt noch offiziell empfohlen.

Alle genannten Marken, Produktnamen und Dienstleistungsbezeichnungen sind Eigentum der jeweiligen Rechteinhaber.

*2026 lfm-player.Die Verwendung erfolgt auf eigene Gefahr!*
---

Nutzt Universal laut.fm Webplayer:  
https://github.com/lfm-player/stream.laut.fm
