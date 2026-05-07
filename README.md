# SKALES – Einfache Anleitung für Einsteiger

![Platform](https://img.shields.io/badge/Plattform-Windows%20%7C%20macOS%20%7C%20Linux-blue)
![Level](https://img.shields.io/badge/Zielgruppe-Einsteiger%20%26%20DAU-success)
![AI Providers](https://img.shields.io/badge/Provider-15%2B-orange)
![Local AI](https://img.shields.io/badge/Lokale%20Modelle-Ollama-informational)
![License](https://img.shields.io/badge/Lizenz-BSL--1.1-lightgrey)
![Language](https://img.shields.io/badge/Sprache-DE-red)


## Was ist SKALES?

**SKALES** ist ein lokaler KI-Desktop-Agent. Das Programm läuft direkt auf deinem Computer und unterstützt laut Projektbeschreibung mehr als 15 KI-Anbieter; zusätzlich kann es mit lokalen Modellen über Ollama arbeiten.[web:2][web:39][web:22]

Das Ziel ist ein möglichst einfacher Einstieg: installieren, API-Key eintragen, Modell auswählen und direkt loslegen. Die offizielle Dokumentation beschreibt dafür einen Onboarding-Ablauf mit Sprache, Provider, API-Key und Standardmodell.[web:22][web:31]

## Projekt-Links

- GitHub-Repository: [skalesapp/skales](https://github.com/skalesapp/skales) [web:1]
- GitHub-Organisation: [skalesapp auf GitHub](https://github.com/skalesapp) [web:2]
- Download-Seite: [getskales.app/download](https://getskales.app/download/) [web:31]
- Offizielle Doku: [docs.skales.app](https://docs.skales.app) [web:22]
- Releases: [GitHub Releases](https://github.com/skalesapp/skales/releases) [web:1]


## Screenshots & Demos

Detaillierte Screenshots und Video-Demos findest du auf den offiziellen Seiten:

- Produktseite mit UI-Screenshots: [skales.app](https://skales.app)  
- Feature-Übersicht mit Studio-, Codework- und Orga-Ansichten: [getskales.app/features](https://getskales.app/features/)  
- Demos in Aktion (Video): [Skales Demo](https://getskales.app/demo/)


<!-- SKALES-AUTO-STATUS-START -->
_Automatisch aktualisierter Status:_

- Letztes Checkdatum: 2026-05-07
- Download-Seite erreichbar: ✅
- Unterstützte OS (laut Download-Seite): Windows, macOS, Linux (Beta)
- Neueste Version (GitHub Releases): v0.0.0 (veröffentlicht am 1970-01-01)
- Kurzbeschreibung des letzten Releases: Platzhalter, wird automatisch überschrieben
<!-- SKALES-AUTO-STATUS-END -->


## Für wen ist das gedacht?

SKALES ist gut geeignet für alle, die eine KI lokal als Desktop-Anwendung nutzen möchten, aber **keine** Lust auf Docker, Terminal-Konfiguration oder komplexe Entwicklungsumgebungen haben.[web:31][web:32] Die Projektbeschreibung nennt Windows, macOS und Linux; die Doku betont zusätzlich, dass keine Registrierung nötig ist und Daten lokal im Benutzerordner gespeichert werden.[web:31][web:22]

## Systemvoraussetzungen

Laut Download-Seite brauchst du:[web:31]

- Windows 10 oder neuer, **oder** macOS 12 oder neuer, **oder** Linux x64 (Beta)  
- Mindestens 4 GB RAM  
- Etwa 500 MB freier Speicherplatz  
- Internetzugang für Cloud-KI-Anbieter; für lokale Nutzung mit Ollama ist das nicht nötig  

## Installation für Anfänger

### 1. Programm herunterladen

Öffne die offizielle Download-Seite: [getskales.app/download](https://getskales.app/download/).[web:31]

Wähle dort dein Betriebssystem aus:[web:31]

- **Windows:** Installer als `.exe`  
- **macOS:** Version für Apple Silicon oder Intel  
- **Linux:** AppImage oder `.deb` (Beta)  

### 2. Installation starten

#### Windows

- Lade die `.exe` herunter.[web:31]  
- Starte die Datei per Doppelklick.  
- Wenn Windows eine SmartScreen-Warnung anzeigt, klicke auf **„More info / Weitere Informationen“** und dann auf **„Run anyway / Trotzdem ausführen“**.[web:31]  

#### macOS

- Lade die passende `.dmg` herunter.[web:31]  
- Öffne die Datei.  
- Ziehe **Skales** in den Programme-Ordner.  
- Falls Gatekeeper warnt, öffne die App per Rechtsklick und dann **Öffnen**.[web:31]  

#### Linux

- Am einfachsten ist die **AppImage-Version**.[web:31]  
- Lade die Datei herunter.  
- Mache sie ausführbar, zum Beispiel per `chmod +x Skales.AppImage`.  
- Starte danach die Datei mit `./Skales.AppImage`.  

> Hinweis: Laut offizieller Download-Seite ist Linux noch **Beta**.[web:31]

### 3. Ersteinrichtung

Die offizielle Doku beschreibt den ersten Start in vier Schritten: Sprache wählen, Provider auswählen, API-Key eintragen und Standardmodell festlegen.[web:22][web:34] Danach landest du direkt im Chat.

## API-Key: Was ist das überhaupt?

Ein API-Key ist ein Zugangsschlüssel für einen KI-Anbieter. SKALES selbst verbindet sich mit externen oder lokalen Modellen; für Cloud-Anbieter brauchst du daher einen passenden Schlüssel, für rein lokale Modelle über Ollama nicht zwingend.[web:22][web:31]

## Wo bekomme ich einen API-Key her?

### Empfohlen für Anfänger: OpenRouter

SKALES empfiehlt in der Dokumentation und auf der OpenRouter-Partnerseite **OpenRouter** als flexiblen Einstieg, weil du damit mit einem einzigen API-Key auf viele Modelle zugreifen kannst.[web:22][web:17][web:20]

Typischer Ablauf:[web:17]

1. Öffne [openrouter.ai](https://openrouter.ai/) im Browser.  
2. Erstelle ein Konto.  
3. Gehe zu `openrouter.ai/settings/keys`.  
4. Erzeuge dort einen neuen API-Key.  
5. Hinterlege ggf. Guthaben, wenn das gewünschte Modell kostenpflichtig ist.  
6. Kopiere den Schlüssel sofort und speichere ihn sicher.  

> Wichtig: API-Keys niemals öffentlich in GitHub hochladen oder in Screenshots zeigen. Öffentlich geleakte Schlüssel werden oft missbraucht oder gesperrt.[web:12]

## API-Key in SKALES eintragen

Die offizielle Dokumentation nennt dafür den Weg über **Settings → Providers** bzw. im Onboarding direkt beim ersten Start.[web:22]

So gehst du vor:

1. Starte SKALES.[web:22]  
2. Öffne **Settings → Providers** oder nutze den Einrichtungsassistenten.  
3. Wähle deinen Anbieter, zum Beispiel **OpenRouter**.[web:22][web:17]  
4. Füge deinen API-Key in das passende Feld ein.  
5. Speichere die Eingabe.  
6. Wähle ein Standardmodell aus.  

## Eigene Modelle installieren und unter SKALES konfigurieren

Es gibt in SKALES zwei einfache Wege für **eigene Modelle**: lokale Modelle über **Ollama** oder externe bzw. selbst gehostete Modelle über **Custom Endpoint**. Die offizielle Doku nennt beide Wege ausdrücklich als unterstützte Provider-Optionen.[web:22][web:39]

### Variante A: Eigene lokale Modelle mit Ollama

SKALES unterstützt **Ollama** als lokalen Provider. Dafür muss Ollama separat installiert sein; danach kannst du lokale Modelle in SKALES verwenden, ohne dass Daten an einen Cloud-Anbieter geschickt werden.[web:22][web:39]

#### Schritt 1: Ollama installieren

Installiere zuerst Ollama auf deinem Rechner. Die SKALES-Dokumentation nennt Ollama als Voraussetzung für vollständig lokale Modelle.[web:22]

Offizielle Seite: [docs.ollama.com](https://docs.ollama.com/).[web:21]

#### Schritt 2: Modell in Ollama laden

Ein typischer Start ist, ein Modell per Terminal zu laden, zum Beispiel:

```bash
ollama pull llama3
```

Ollama unterstützt darüber hinaus auch das Importieren eigener Adapter und das Erstellen angepasster Modelle über `Modelfile` und `ollama create`.[web:21]

#### Schritt 3: SKALES mit Ollama verbinden

1. Öffne in SKALES **Settings → Providers**.[web:22]  
2. Aktiviere **Ollama** als Provider.[web:22]  
3. Aktualisiere bei Bedarf die Modellliste; laut Doku gibt es dafür pro Provider eine **Refresh**-Funktion.[web:22]  
4. Wähle dein geladenes Ollama-Modell als Standardmodell oder im Chat über den Model-Picker.[web:22]  

#### Schritt 4: Modell im Chat wechseln

Laut Doku kannst du Modelle direkt im laufenden Betrieb wechseln, entweder über den Modellwähler oder mit dem Chat-Befehl `/model`.[web:22]

Beispiel:

```text
/model llama3
```

### Variante B: Eigene oder fremde Modelle über OpenRouter

Wenn du **kein lokales Modell selbst hosten** willst, ist OpenRouter der einfachste Weg, um viele verschiedene Modelle mit einem einzigen API-Key unter SKALES verfügbar zu machen.[web:17][web:20] Die OpenRouter-Seite zu SKALES beschreibt genau diesen Einsatzfall.[web:17]

So gehst du vor:

1. OpenRouter-Key anlegen.[web:17]  
2. In SKALES **OpenRouter** als Provider auswählen.[web:22]  
3. API-Key eintragen.  
4. Modellliste aktualisieren.  
5. Passendes Modell auswählen.  

### Variante C: Eigene Server oder lokale APIs mit Custom Endpoint

Die offizielle SKALES-Doku nennt außerdem **Custom Endpoint** für jede OpenAI-kompatible API, zum Beispiel **LM Studio**, **KoboldCpp**, **vLLM** oder andere lokale Server.[web:22]

Das ist sinnvoll, wenn du:

- einen eigenen lokalen Inferenzserver betreibst,  
- ein Modell im Schulnetz oder Heimnetz bereitstellst,  
- oder eine OpenAI-kompatible API selbst hostest.  

#### Grundkonfiguration in SKALES

1. Öffne **Settings → Providers**.[web:22]  
2. Wähle **Custom Endpoint**.  
3. Trage die URL deiner API ein.  
4. Hinterlege falls nötig einen API-Key.  
5. Aktualisiere die Modellliste.  
6. Wähle das gewünschte Modell aus.  

## Modelle in SKALES sinnvoll konfigurieren

Die Doku beschreibt mehrere Möglichkeiten, Modelle zu verwalten: über den Provider-Bereich, über den Chat-Modellwähler und per `/model`-Befehl direkt im Chat.[web:22] Außerdem können mehrere Provider parallel eingerichtet und während einer Sitzung gewechselt werden.[web:22]

Für Fortgeschrittene gibt es zusätzlich **Override Model Limits** in **Settings → AI Providers → Override Model Limits**. Dort lassen sich laut Doku pro Provider und Modell Kontext- und Ausgabegrenzen anpassen, auch mit Wildcard `*` für providerweite Regeln.[web:22]

### Empfohlene Praxis für Einsteiger

| Zweck                     | Empfehlung    | Begründung                                                                 |
|--------------------------|--------------|----------------------------------------------------------------------------|
| Einfach starten          | OpenRouter   | Ein API-Key für viele Modelle.[web:17][web:20]                             |
| Datenschutz / lokal      | Ollama       | Daten bleiben auf dem eigenen Rechner.[web:22][web:21]                     |
| Eigene Infrastruktur     | Custom Endpoint | Für OpenAI-kompatible eigene APIs.[web:22]                             |
| Modellwechsel im Alltag  | `/model` oder Model-Picker | Direkt im Chat umschaltbar.[web:22]                       |

## Empfohlene Ersteinstellungen

Wenn du möglichst einfach starten willst, nutze diese Reihenfolge:

- Anbieter: **OpenRouter**.[web:17][web:34]  
- Danach einen einfachen Standard-Chat testen.  
- Später lokale Modelle mit Ollama ergänzen.[web:22][web:21]  
- Erst dann Spezialanbieter oder Custom Endpoints einrichten.[web:22]  

## Erste Schritte nach der Installation

Nach der Einrichtung landest du direkt im Chat. Dort kannst du laut Doku Dateien anhängen, Modelle wechseln, mehrere Sessions verwalten und verschiedene Provider parallel nutzen.[web:22]

Sinnvolle erste Tests:

- Schreibe: „Erkläre mir dieses Programm.“  
- Bitte die KI um eine kurze Zusammenfassung eines Textes.  
- Teste: „Erstelle mir drei differenzierte Aufgaben für Klasse 7.“  
- Wechsle danach probeweise das Modell über den Model-Picker oder `/model`.[web:22]  

## Typische Probleme

### SKALES startet nicht

- Prüfe, ob dein Betriebssystem unterstützt wird.[web:31]  
- Prüfe, ob genug Speicherplatz vorhanden ist.[web:31]  
- Lade die Datei notfalls neu von der offiziellen Download-Seite.[web:31]  

### API-Key funktioniert nicht

- Prüfe, ob der Key vollständig kopiert wurde.  
- Prüfe, ob du den richtigen Anbieter in SKALES ausgewählt hast.[web:22]  
- Erstelle notfalls beim Anbieter einen neuen Schlüssel.  

### Eigenes Modell erscheint nicht in SKALES

- Prüfe bei Ollama, ob das Modell wirklich lokal installiert ist.[web:21]  
- Nutze in SKALES die **Refresh**-Funktion im Provider-Bereich, damit die aktuelle Modellliste neu geladen wird.[web:22]  
- Prüfe beim Custom Endpoint, ob deine API wirklich OpenAI-kompatibel erreichbar ist.[web:22]  

### Unter Linux passiert nichts

- Prüfe, ob die AppImage-Datei ausführbar ist.[web:31]  
- Nutze alternativ die `.deb`-Version, falls dein System Debian/Ubuntu-basiert ist.[web:31]  
- Beachte, dass Linux laut offizieller Seite noch Beta ist.[web:31]  

## Sicherheit

Beachte diese Grundregeln:[web:12]

- API-Keys nie in öffentliche Repositories hochladen.[web:12]  
- API-Keys nie in Foren, Tickets oder Chats posten.[web:12]  
- Bei Verdacht auf Missbrauch den Key sofort löschen und neu erstellen.[web:12]  

## Lizenz und Projektstatus

Die Download-Seite beschreibt SKALES als **source-available** unter **BSL-1.1** auf GitHub.[web:31][web:2]

Zusätzlich beschreibt die GitHub-Präsenz das Projekt als lokalen KI-Desktop-Agenten mit vielen Providern und lokalem Betrieb über Ollama.[web:2][web:39]

---
