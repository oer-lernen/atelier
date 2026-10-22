# 🎨 Kommas Atelier

**Ein fröhliches Malprogramm für Kinder – mit der Pixelkatze Komma.**
Kommas Atelier lädt Kinder zum freien, ästhetischen Gestalten ein: zeichnen, füllen, stempeln, zaubern – und wenn das Bild fertig (oder misslungen) ist, macht die Bombe die Leinwand mit großem Knall wieder frei. Das Programm ist inspiriert von klassischen Kinder-Malprogrammen der 90er-Jahre, im cozy Retro-Pixel-Look mit Pastellfarben.
Alles steckt in **einer einzigen HTML-Datei** und erfordert keine Installation, Anmeldung oder Datenübertragung.

---

## ✨ Funktionen
| Werkzeug | Was es kann |
|---|---|
| ✏️ **Stift** | knackige Pixel-Linien in drei Größen |
| 🖌️ **Pinsel** | weiche, runde Striche in drei Größen |
| 💨 **Sprühdose** | Sprühnebel, der beim Stillhalten dichter wird |
| 🪄 **Zauberpinsel** | Regenbogen, Spiegel, Kaleidoskop, Sterne, Blasen, Konfetti |
| 📏 **Linie** | gerade Linien in drei Stärken |
| 🔷 **Formen** | Rechteck und Kreis, leer oder gefüllt |
| 🪣 **Farbeimer** | Flächen füllen – einfarbig, Punkte, Streifen, Karo oder Regenbogen |
| 🔖 **Stempel** | 15 Pixelmotive (u. a. Komma, Herz, Stern, Sonne, Blume, Baum, Haus, Zug, Fenster, Tür) in drei Größen; die **Ziegelmauer** rastet im Raster ein, sodass nahtlose Mauern entstehen |
| 🧽 **Radierer** | in drei Größen |
| 🎩 **Zaubertricks** | das ganze Bild spiegeln, auf den Kopf stellen, Farben vertauschen oder verpixeln |

**Außerdem:**
- ↩️ **Rückgängig** – nimmt den letzten Schritt zurück (mit Spul-Effekt); ein zweiter Tipp stellt ihn wieder her
- 💣 **Bombe** – die Zündschnur zischt, das Bild zerspringt in fliegende Stücke. Auch das lässt sich rückgängig machen.
- 💾 **Speichern** – lädt das Bild als PNG-Datei auf das eigene Gerät
- ⛶ **Vollbild** – blendet die Browserleiste aus (wird auf Geräten ohne Unterstützung automatisch ausgeblendet)
- 🔊 **Ton an/aus** – alle Klänge werden live im Browser erzeugt
- 🏠 **Zur Startseite** – führt zu prima.kommakatze.de (fragt vorher, weil ein ungespeichertes Bild verloren ginge; offline ausgeblendet)
- 🐱 **Komma** – blinzelt, freut sich mit Herzchen und Sternen und miaut, wenn man sie antippt
- ⌨️ **Strg + Z** – Rückgängig per Tastatur

---

## 🚀 Nutzung
Die Datei kann heruntergeladen werden und läuft auch komplett offline mit jedem aktuellen Browser.


## 🛠️ Technik
- reines HTML, CSS und JavaScript – ohne Frameworks, ohne Build-Schritt
- Zeichnen auf `<canvas>` (interne Auflösung 1200 × 800 px, Seitenverhältnis 3 : 2)
- Pixelgrafiken (Symbole, Stempel, Komma) als Zeichen-Raster direkt im Code definiert
- Soundeffekte über die Web Audio API
- Pointer Events für Maus, Touch und Stift
Eigene Stempel lassen sich im Code im Abschnitt `STAMPS` ergänzen: Jedes Motiv ist ein Raster aus Zeichen, denen in der Palette `SP` eine Farbe zugeordnet ist.

---

## 📄 Lizenz
**„Kommas Atelier“** von Sebastian Wolf steht unter der Lizenz [Creative Commons Namensnennung – Weitergabe unter gleichen Bedingungen 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.de).
Du darfst das Programm teilen und bearbeiten – auch für den Unterricht und in eigenen Projekten –, wenn du den Urheber und die Lizenz nennst und Bearbeitungen unter derselben Lizenz weitergibst.
Die Bilder, die mit dem Programm gemalt werden, gehören den Kindern, die sie gemalt haben.
**Transparenzhinweis:** Programmiert mit Unterstützung von KI (Claude, Anthropic). Idee, Inhalte und fachliche Prüfung: Sebastian Wolf. 