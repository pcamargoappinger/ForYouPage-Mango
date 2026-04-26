# Klassen-Feed

Ein einfacher Social-Media-Feed für den Klassenraum – hostbar über GitHub Pages.

## Einrichtung

### 1. Repository erstellen
1. Gehe auf [github.com](https://github.com) und melde dich an
2. Klicke oben rechts auf **„+"** → **„New repository"**
3. Name: `klassen-feed` (oder beliebig)
4. Sichtbarkeit: **Public** (notwendig für GitHub Pages kostenlos)
5. Klicke **„Create repository"**

### 2. Dateien hochladen
1. Im neuen Repository auf **„uploading an existing file"** klicken
2. Alle Dateien aus diesem Ordner hochladen (`index.html`, `README.md`, `_config.yml`)
3. Commit-Nachricht eingeben, z. B. `Klassen-Feed hinzugefügt`
4. Auf **„Commit changes"** klicken

### 3. GitHub Pages aktivieren
1. Im Repository auf **„Settings"** klicken
2. Links im Menü: **„Pages"**
3. Unter „Source": Branch **`main`** auswählen, Ordner **`/ (root)`**
4. Auf **„Save"** klicken
5. Nach 1–2 Minuten ist die Seite erreichbar unter:
   ```
   https://DEIN-USERNAME.github.io/klassen-feed/
   ```

### 4. QR-Code
- Melde dich als Admin an (Passwort: `lehrer123`)
- Gehe zu **„Beiträge verwalten"**
- Der QR-Code wird automatisch mit deiner GitHub-Pages-URL generiert

## Nutzung

| Funktion | Beschreibung |
|---|---|
| **Feed-Ansicht** | Standardansicht für Schüler:innen |
| **Admin-Login** | Oben rechts → Passwort eingeben |
| **Beitrag erstellen** | Text, Bild, Kategorie, Autor |
| **Passwort ändern** | Im Admin-Bereich unter „Einstellungen" |

## Hinweis zur Datenspeicherung

Beiträge werden im `localStorage` des Browsers gespeichert.  
Das bedeutet: Beiträge sind nur auf dem Gerät sichtbar, auf dem du sie erstellt hast.  
Schüler:innen sehen die Beiträge **nicht** – dafür ist ein Backend nötig (z. B. Firebase).  
Für eine einfache Lösung: Beiträge erstellen → Screenshot → als Bild-Post teilen.

> **Tipp:** Für echte Synchronisation über Geräte hinweg → Erweiterung mit Firebase Realtime Database möglich.
