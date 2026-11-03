# laut.fm Now Playing Widget

Mit dem kostenlosen laut.fm Now Playing Widget kannst du deinen Radiosender ganz einfach auf deiner eigenen Homepage präsentieren.

Das Widget zeigt automatisch, welcher Sender gerade läuft, welcher Interpret zu hören ist und wie der aktuelle Musiktitel heißt. Dazu wird das passende Künstlerbild oder – falls keines verfügbar ist – das Senderlogo angezeigt.

**Kostenlos, unkompliziert und ohne eigene technische Infrastruktur.**

Das Widget spielt selbst keine Musik ab. Die Wiedergabe erfolgt über den Universal laut.fm Webplayer.

🌐 **Live ausprobieren:**  
https://lfm-player.github.io/Now-Playing-Widget/

Die Verwendung erfolgt auf eigene Gefahr!!

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

Ersetze eins einfach durch den Namen deines eigenen laut.fm-Senders.

Tipp: Passe bei Bedarf die Höhe (height) und die maximale Breite (max-width) an das Design deiner Homepage an.

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
- Cover Anzeige: `https://api.laut.fm/station/{station}/cover` 

Die Audiowiedergabe erfolgt über den jeweiligen laut.fm-Stream.

## 🔧 Verwendete Technologien

- HTML5
- CSS3
- JavaScript
- laut.fm API
- laut.fm Audio-Streaming
- GitHub Pages
- Nutzt Universal laut.fm Webplayer nach klick auf "Im Webplayer öffnen" öffnet sich ein neuer externer Player.

Das Widget benötigt keine eigene Datenbank und kein PHP-Backend.

## 🌍 Hosting

Das Now Playing Widget wird über **GitHub Pages** bereitgestellt.

Das Projekt ist als statische Website umgesetzt und benötigt keinen eigenen Webserver mit serverseitiger Programmlogik.

## 📄 Lizenz und Hinweise

Dieses Projekt ist ein unabhängiges Now Playing Widget Anzeige-Projekt zur Titelanzeige von laut.fm-Radiosendern.

laut.fm ist eine eigenständige Plattform. Markenrechte und Rechte an den bereitgestellten Inhalten verbleiben bei den jeweiligen Rechteinhabern.

Die Verfügbarkeit der Senderinformationen, Coverbilder und Audiostreams hängt von laut.fm und den jeweiligen Datenquellen ab.

---
Nutzt Universal laut.fm Webplayer https://github.com/lfm-player/stream.laut.fm
