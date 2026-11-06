<p align="center">
  <img src="assets/logo.svg" width="96" alt="Sonora IPTV">
</p>

<h1 align="center">Sonora IPTV</h1>

<p align="center">
  <b>Der elegante IPTV-Player für Windows.</b><br>
  Live-TV mit Programmführer, Filme und Serien aus deinem eigenen Xtream- oder M3U-Abo.
</p>

<p align="center">
  <a href="https://github.com/Molulrr/sonora-iptv/releases/latest"><img alt="Neueste Version" src="https://img.shields.io/github/v/release/Molulrr/sonora-iptv?label=Version&color=7c4dff&style=for-the-badge"></a>
  <a href="https://github.com/Molulrr/sonora-iptv/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Molulrr/sonora-iptv/total?label=Downloads&color=9f7aff&style=for-the-badge"></a>
  <img alt="Windows 10 und 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-2f2a44?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/Molulrr/sonora-iptv/releases/latest"><b>⬇️ Download für Windows</b></a>
  &nbsp;·&nbsp;
  <a href="https://molulrr.github.io/sonora-iptv/"><b>🌐 Webseite</b></a>
  &nbsp;·&nbsp;
  <a href="#anleitung"><b>📖 Anleitung</b></a>
</p>

<p align="center">
  <img src="assets/screenshots/home.webp" alt="Sonora IPTV – Startseite" width="900">
</p>

---

## ✨ Funktionen

| | |
|---|---|
| 📺 **Live-TV mit Vorschau** | Kategorien, Senderliste und große Live-Vorschau nebeneinander. |
| 🗓️ **Programmführer (EPG)** | Was läuft jetzt, was kommt danach – automatisch geladen. |
| 🎬 **Filme & Serien** | Poster, Beschreibung, Besetzung, Staffeln, Episoden und Trailer. |
| ⏯️ **Weiterschauen** | Filme und Folgen starten dort, wo du aufgehört hast. |
| ▶️ **mpv-Wiedergabe** | Hardware-Decodierung, Deinterlacing, Tonspuren, Untertitel. |
| 🪟 **Mini-Player** | Weiter stöbern, während das Video läuft. |
| 🔎 **Suche & Favoriten** | Eine Suche für alles, eigene Lieblings-Kategorien. |
| 🔒 **Sicher** | Zugangsdaten liegen in der Windows-Anmeldeinformationsverwaltung. |
| 🌍 **6 Sprachen** | Deutsch, Englisch, Französisch, Spanisch, Italienisch, Türkisch. |
| 🔄 **Automatische Updates** | Neue Versionen mit einem Klick installieren. |

## 🖼️ Screenshots

| Live-TV | Filme |
|---|---|
| ![Live-TV](assets/screenshots/live-tv.webp) | ![Filme](assets/screenshots/movies.webp) |
| **Filmdetails** | **Serien** |
| ![Filmdetails](assets/screenshots/movie-details.webp) | ![Serien](assets/screenshots/series-details.webp) |

## ⬇️ Installation

1. Lade die neueste **`Sonora.IPTV_<Version>_x64-setup.exe`** unter [Releases](https://github.com/Molulrr/sonora-iptv/releases/latest) herunter.
2. Starte die Datei per Doppelklick und folge den Anweisungen (keine Administratorrechte nötig).
3. Öffne Sonora IPTV und füge deinen Anbieter hinzu.

> [!NOTE]
> Zeigt Windows **„Der Computer wurde durch Windows geschützt“**, klicke auf **„Weitere Informationen“** → **„Trotzdem ausführen“**. Das passiert, weil die App noch neu ist.

## <a id="anleitung"></a>📖 Anleitung

### Anbieter mit Xtream Codes
1. **Einstellungen → Anbieter → „Anbieter hinzufügen“**
2. **Xtream Codes** wählen, Namen vergeben
3. **Server-URL**, **Benutzername** und **Passwort** eintragen
4. **„Verbindung testen“** → **„Speichern“**

### Anbieter mit M3U-/M3U8-Playlist
1. **Einstellungen → Anbieter → „Anbieter hinzufügen“**
2. **M3U-/M3U8-Playlist** wählen
3. **Playlist-URL** einfügen oder eine **Datei** auswählen
4. Optional einen **Programmführer (XMLTV)** angeben → **„Speichern“**

### Tastenkürzel im Player

| Taste | Funktion |
|---|---|
| `Leertaste` / `K` | Wiedergabe / Pause |
| `F` | Vollbild |
| `M` | Ton aus / an |
| `↑` / `↓` | Lautstärke |
| `←` / `→` | 10 Sekunden zurück / vor |
| `Bild ↑` / `Bild ↓` | Vorheriger / nächster Sender |
| `Esc` | Vollbild verlassen / Player verkleinern |

### Probleme?
- **Stream ruckelt:** Einstellungen → Live-TV → *Live-Stream-Format* auf **HLS** stellen oder den **Netzwerkpuffer** erhöhen.
- **Video bleibt schwarz:** Einstellungen → Wiedergabe → *Videoausgabe* auf **Separates Fenster** stellen.
- **Bildfehler:** **Hardware-Decodierung** ausschalten.

Weitere Fragen beantwortet die [FAQ auf der Webseite](https://molulrr.github.io/sonora-iptv/#faq). Fehler gefunden? [Problem melden](https://github.com/Molulrr/sonora-iptv/issues).

## 💻 Systemanforderungen

- Windows 10 oder 11 (64-Bit)
- ca. 150 MB freier Speicher
- Internetverbindung (ab 10 Mbit/s für HD)
- Ein eigenes IPTV-Abo (Xtream Codes oder M3U)

---

<sub>Sonora IPTV ist ein Medienplayer und stellt keine Inhalte, Sender oder Abonnements bereit. Nutze ihn ausschließlich mit Inhalten, zu deren Wiedergabe du berechtigt bist. Wiedergabe mit [mpv](https://mpv.io) (GPL/LGPL). © 2026 Sonora IPTV.</sub>
