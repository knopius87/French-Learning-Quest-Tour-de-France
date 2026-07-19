  # France Quest

  **Eine spielerische Tour de France durch die französische Sprache.**  
  Reise-Französisch auf Niveau A2/B1 · mobil · offlinefähig · ohne Anmeldung

  ![HTML](https://img.shields.io/badge/HTML-5-e34f26?style=flat-square)
  ![CSS](https://img.shields.io/badge/CSS-Dark_Mode-1572b6?style=flat-square)
  ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-f7df1e?style=flat-square&logoColor=111)
  ![PWA](https://img.shields.io/badge/PWA-offline-6b5cff?style=flat-square)
</div>

## Über die App

France Quest verwandelt Reise-Französisch in eine virtuelle Radrundfahrt. Jede französische Stadt ist eine Etappe mit eigener Landschaft, Farbwelt und einem typischen Gesprächsthema. Die Reise beginnt in Strasbourg und endet mit dem Grand Final in Paris.

Die App läuft direkt im Browser, benötigt keinen Build-Schritt und speichert den Lernfortschritt ausschließlich lokal auf dem Gerät.

## Das bietet France Quest

- 12 thematische Reiseetappen von Strasbourg bis Paris
- 168 Vokabeln mit Beispielsätzen
- 84 Scaffolds als Gerüste für eigene Gesprächsbeiträge
- 24 französische Lückensätze
- 12 dreistufige Conversation Challenges
- Aufgaben von Deutsch nach Französisch und Französisch nach Deutsch
- Multiple Choice, Lückentext und vollständig getippte Antworten
- 8 Grammatikpässe zu zentralen A2/B1-Themen
- freier Übe-Modus für einzelne Städte oder die gesamte Tour
- XP, Herzen, Lernserie, Münzen, Konfetti und Etappen-Abzeichen
- wechselnde dunkle Landschaften passend zur jeweiligen Region
- installierbar und offlinefähig als Progressive Web App

## Die Route

| Etappe | Stadt | Gesprächsthema | Kulisse |
|---:|---|---|---|
| 1 | Strasbourg | Begrüßen und Small Talk | Altstadt am Rhein |
| 2 | Colmar | Anreise und Gepäck | Weinberge im Elsass |
| 3 | Annecy | Orientierung und Nahverkehr | Alpen und Bergsee |
| 4 | Lyon | Unterkunft und Reservieren | Großstadt an der Rhône |
| 5 | Avignon | Restaurant und Café | Provence |
| 6 | Marseille | Apotheke und Gesundheit | Mittelmeerküste |
| 7 | Nice | Wetter und Freizeitpläne | Riviera |
| 8 | Toulouse | Markt und Einkaufen | Südfranzösische Stadt |
| 9 | Bordeaux | Fußball und Small Talk | Weinland an der Garonne |
| 10 | Nantes | Probleme und Notfälle | Atlantik und Loire |
| 11 | Lille | Einladung, Kultur und Abschied | Nordfranzösische Stadtkulisse |
| 12 | Paris | gemischtes Grand Final | Lichter der Hauptstadt |

Jede Etappe führt in drei Mini-Étapes neue Wörter und Gesprächsgerüste ein. Danach folgt die Conversation Challenge in fester Lernprogression:

1. passende Antwort als Multiple Choice erkennen
2. eine französische Antwort als Lückentext ergänzen
3. eine vollständige Antwort selbst formulieren

## Auf dem Smartphone installieren

- **iPhone/iPad:** GitHub-Pages-Adresse in Safari öffnen → Teilen → **Zum Home-Bildschirm**
- **Android:** Adresse in Chrome öffnen → Browsermenü → **App installieren**

Danach lässt sich France Quest wie eine normale App vom Homescreen starten.

## Projektstruktur

```text
france-quest/
├── index.html            # Startseite der App
├── styles.css            # Dark Mode, Landschaften und Icon-Design
├── app.js                # Lerninhalte, Übungen und Spiellogik
├── icon.svg              # App-Icon
├── manifest.webmanifest  # Installation als PWA
├── sw.js                 # Offline-Cache
├── .nojekyll             # direkte Auslieferung über GitHub Pages
└── README.md             # diese Projektbeschreibung
```

## Datenschutz

Die App verwendet keine Konten, Werbung oder externen Lerndienste. XP, Herzen, Serie und Lernfortschritt bleiben im lokalen Speicher des jeweiligen Browsers.
