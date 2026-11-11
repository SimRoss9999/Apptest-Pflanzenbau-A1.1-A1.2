# Liebegg Trainer

Prüfungstrainer für die Berufsfachschule Liebegg, ZWAL 1. Am Start wählst du die Prüfung:

- **Pflanzenbau A1.1 und A1.2**: Boden befahren und bearbeiten (302 Fragen)
- **Tierhaltung B1.1 und B1.2**: Mit Rindern artgerecht und sicher umgehen, für das Wohlbefinden der Tiere sorgen (175 Fragen)
- **Pflanzenbau A6.2**: Mischungen für Kunstwiesen wählen und bewirtschaften (287 Fragen)

Statische Webapp ohne Build-Schritt und ohne Backend. Für die Bedienung am Handy gebaut.

## Was drin ist

- 764 Multiple-Choice-Fragen in drei Prüfungen, jede mit Erklärung und Quellenangabe
- Pro Prüfung eigene Themenbereiche plus Modus «Alles»
- Pro Prüfung ein eigener Verlauf
- Frei wählbare Fragenzahl pro Durchlauf (10 / 20 / 30 / 50 / alle)
- Fragen und Antwortoptionen werden bei jedem Durchlauf neu gemischt
- Sofortiges Feedback nach jeder Antwort
- Auswertung am Ende mit allen Fragen zum Nachlesen; falsch beantwortete sind aufgeklappt
- Verlauf der letzten 40 Durchläufe, lokal im Browser gespeichert
- Tastaturbedienung am Desktop: `A`–`D` zum Antworten, `Enter` für weiter

## Prüfung Pflanzenbau A6.2

Die Fragen folgen den Lernzielen und Lernaufgaben L1 bis L34. Inhaltlich hat die PowerPoint Vorrang, das Buch ergänzt. Wo sich die beiden widersprechen, gilt die PowerPoint (zum Beispiel pH für Luzerne mindestens 6.5 statt 6.2, Grünhafer als Deckfrucht 30 bis 80 kg/ha). Die falschen Antworten stammen aus Nachbarfakten, etwa andere Mischungsnummern, Etikettenfarben, Auflaufgruppen oder Saattermine. Die richtige Antwort ist in 18 % der Fragen allein die längste, also seltener als bei Zufall.

| Bereich | Lernaufgaben | Fragen |
|---|---|---|
| Begriffe und Bedeutung der Kunstwiese | L1 bis L3 | 18 |
| Arten und Standardmischungen (Codes) | L4, L5, L7, L8, L11, L13 | 26 |
| Nutzungsdauer, Nutzungsart und Intensität | L6, L9 | 22 |
| Raigrasfähigkeit und Mischungswahl | L10, L15, L16 | 28 |
| Luzerne | L12 | 20 |
| Deckfrucht und Saatgutqualität | L14 | 18 |
| Saatzeitpunkt und Bodenbearbeitung | L17 bis L20 | 26 |
| Saatverfahren, Saattiefe und Walzen | L21, L22 | 23 |
| Pflege beim Auflaufen und Unkraut | L23, L24 | 20 |
| Herbizide und Übersaat bei Neuansaaten | L25, L26 | 16 |
| Bewirtschaften, Ablöseprinzip und Dauerwiese | L27 bis L32 | 39 |
| Zwischenfutter | L33, L34 | 31 |

Nicht enthalten: die Aufgabe L23 als Zeitachse (dafür Fragen zu den Auflaufgruppen) und L34e (eigener Betrieb).

## Prüfung Tierhaltung

Die Fragen stammen aus den Lernzielen und den Arbeitsdossiers mit Lösungen (Hauptbasis), dem Heft, den Präsentationen und dem Arbeitsblatt Tierwohlprogramme. Die falschen Antworten sind so gebaut, dass sie aus Nachbarfakten oder typischen Rechenfehlern entstehen. Die Antwortlängen sind ausgeglichen, die richtige Antwort ist nicht systematisch die längste.

| Bereich | Fragen |
|---|---|
| Sinneswahrnehmungen des Rindes | 16 |
| Reaktion, Kopfhaltung und Gefahren | 15 |
| Beziehung zum Rind aufbauen | 8 |
| Herde, Auslauf, Treiben und Beobachten | 20 |
| Fellpflege | 5 |
| Tierschutz, Kuhsignale und Kuhtrainer | 17 |
| BTS, RAUS, Weidebeitrag und Beiträge | 20 |
| Liegebereich und Stallsysteme | 20 |
| Fressen und Trinken | 13 |
| Laufbereich, Böden und behornte Kühe | 10 |
| Licht, Temperatur, Feuchtigkeit und Schadgase | 23 |
| Zusatz (Heft Kap. 4, nicht in den Lernzielen) | 8 |

Nicht enthalten: Anatomie (braucht die Abbildungen) und Inhalte des Kontrollhandbuchs. Die Beitragstabelle wird über die Sätze aus dem Arbeitsblatt gerechnet.

## Quellen der Fragen (Pflanzenbau)

| Quelle | Umfang |
|---|---|
| Lerndossier mit Lösungen | L1–L60 inkl. Begriffsteil |
| PowerPoint «A1.1 und A1.2 Boden befahren u. bearbeiten» | bis Folie 132 |
| Lehrbuch A1.1 / A1.2 | ergänzender Fachkontext |

Die Quellenangabe steht bei jeder Frage im Feld `s` und wird im Feedback angezeigt.

## Themenbereiche (Pflanzenbau)

| Bereich | Lernziele | Fragen |
|---|---|---|
| Spatenprobe & Bodenbeurteilung | 1 | 17 |
| Bodenart, Körnung & Bestandteile | 2–5 | 32 |
| Bodengefüge & Bodenporen | 6, 7, 10 | 26 |
| Ton-Humus-Komplex & Kalk | 8, 9 | 15 |
| Humus | 11 | 19 |
| Bodenlebewesen & Regenwurm | 12, 13 | 39 |
| Ernterückstände & Pflanzenbewuchs | 14–16 | 18 |
| Befahrbarkeit, Verdichtung & Radlast | A1.1 Kap. 2 | 35 |
| Pflug, Grubber & Grundbodenbearbeitung | 17–20, 22 | 50 |
| Saatbett, Saattechnik & Direktsaat | 21, 23–25 | 51 |

## Auf GitHub Pages veröffentlichen

1. Neues Repository anlegen, zum Beispiel `liebegg-trainer`.
2. Alle Dateien dieses Ordners ins Repository laden (per Drag-and-drop im Browser oder via Git).
3. Im Repository unter **Settings → Pages** als Source `Deploy from a branch` wählen, Branch `main`, Ordner `/ (root)`.
4. Nach ein bis zwei Minuten läuft die App unter `https://<benutzername>.github.io/liebegg-trainer/`.

Per Kommandozeile:

```bash
git init
git add .
git commit -m "Liebegg Trainer"
git branch -M main
git remote add origin https://github.com/<benutzername>/liebegg-trainer.git
git push -u origin main
```

Auf dem Handy lässt sich die Seite über «Zum Home-Bildschirm hinzufügen» wie eine App installieren.

## Lokal testen

Direktes Öffnen von `index.html` funktioniert. Wer einen lokalen Server bevorzugt:

```bash
python3 -m http.server 8000
```

Dann `http://localhost:8000` aufrufen.

## Fragen ergänzen oder korrigieren

Alle Inhalte stecken in `questions.js`. Eine Frage sieht so aus:

```js
{
  c: 'humus',                         // Kategorie-ID aus CATEGORIES
  q: 'Was ist Humus?',                // Frage
  o: ['Antwort A', 'B', 'C', 'D'],    // 2 bis 5 Optionen
  a: 0,                               // Index der richtigen Antwort (0-basiert)
  e: 'Erklärung nach der Antwort.',   // Erklärung
  s: 'L17'                            // Quelle, optional
}
```

Die Reihenfolge der Optionen wird zur Laufzeit gemischt, `a` bezieht sich immer auf die hier notierte Reihenfolge.

Ein neuer Bereich braucht einen zusätzlichen Eintrag in `CATEGORIES` mit `id`, `name` und `lz`. Die Fragenzahl pro Bereich zählt die App selbst.

## Dateien

```
index.html      App (Layout, Logik, Styles)
questions.js                Kategorien und Fragen Pflanzenbau A1.1 / A1.2
questions-tierhaltung.js    Kategorien und Fragen Tierhaltung B1.1 / B1.2
questions-kunstwiesen.js    Kategorien und Fragen Pflanzenbau A6.2
manifest.json   Metadaten für die Installation am Handy
icon.svg        App-Icon
```

## Datenschutz

Es werden keine Daten übertragen. Der Verlauf liegt ausschliesslich im `localStorage` des jeweiligen Browsers und lässt sich in der App löschen.
