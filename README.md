# laut.fm Now Playing Widget

Ein kompaktes, responsives Now-Playing-Widget für laut.fm-Radiosender. Besucher können zunächst den Stationsnamen eingeben. Danach zeigt das Widget den Sendernamen, Interpret, aktuellen Titel und ein Cover. Wenn kein Songbild verfügbar ist, wird das Senderlogo des ausgewählten Senders verwendet.

Ein Klick auf **Im Webplayer hören** öffnet den passenden Sender im [Universal laut.fm Webplayer](https://lfm-player.github.io/stream.laut.fm/).

## Einbindung



Der Besucher gibt den laut.fm-Stationsnamen direkt im Widget ein.

Du kannst auch einen Sender vorauswählen:

```html
<iframe
  src="https://lfm-player.github.io/now-playing/?station=shout_fm"
  width="100%"
  height="140"
  style="border:0; max-width:640px;"
  loading="lazy"
  title="Shout FM – Now Playing">
</iframe>
```

## Funktionen

- Eingabemaske für den Stationsnamen
- Optionaler URL-Parameter `?station=`
- Offizieller Sendername aus `display_name`
- Aktueller Interpret und Titel aus der laut.fm-API
- Künstlerbild oder Senderlogo als Fallback
- Aktualisierung alle 15 Sekunden
- Klick öffnet den Universalplayer mit dem ausgewählten Sender
- Eigenständiges blaues Design, responsiv für Desktop und Mobilgeräte
- Reines HTML, CSS und JavaScript – keine Datenbank und kein PHP

## API

- `https://api.laut.fm/station/{station}`
- `https://api.laut.fm/station/{station}/current_song`

Das Widget selbst streamt keine Musik. Die Audiowiedergabe erfolgt im Universalplayer über laut.fm.

## Hosting

Für GitHub Pages vorgesehen. `index.html` im Repository ablegen und GitHub Pages unter **Settings → Pages** aktivieren.

## Hinweise

Die Verfügbarkeit von Senderdaten, Bildern und Streams hängt von laut.fm ab. Dieses Projekt ist unabhängig und keine offizielle laut.fm-Anwendung.
