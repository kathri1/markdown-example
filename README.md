# Markdown Cheat-Sheet
## Für das Projekt: `markdownexample` · Velox API README

---

## Überschriften

```markdown
# H1 – Projekttitel         (z. B. # Velox API)
## H2 – Abschnitt           (z. B. ## Installation)
### H3 – Unterabschnitt     (z. B. ### Windows)
#### H4 – Detail
```

---

## Textformatierung

```markdown
**Fett**              → **A lightweight REST API**
*Kursiv*              → *optional*
~~Durchgestrichen~~   → ~~deprecated~~
`Inline-Code`         → `http://localhost:8000`
```

**Ergebnis:** **Fett** · *Kursiv* · ~~Durchgestrichen~~ · `Inline-Code`

---

## Links & Bilder

```markdown
[Linktext](https://github.com/yourname/markdownexample)
![Alternativtext](https://example.com/bild.png)
```

---

## Badges (Shields.io)

```markdown
![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)
![FastAPI 0.111](https://img.shields.io/badge/FastAPI-0.111-009688?logo=fastapi)
![License MIT](https://img.shields.io/badge/License-MIT-green)
```

> Badges werden auf GitHub als bunte Etiketten gerendert.

---

## Code-Blöcke

````markdown
```bash
git clone https://github.com/yourname/velox-api.git
cd velox-api
pip install -r requirements.txt
uvicorn app.main:app --reload
```
````

> Sprache nach den ersten drei Backticks angeben: `bash`, `python`, `json`, …

---

## Tabellen

```markdown
| Method | Endpoint      | Description      |
|--------|---------------|------------------|
| POST   | /auth/login   | Obtain JWT token |
| GET    | /users/me     | Get current user |
| GET    | /items/{id}   | Retrieve item    |
| POST   | /items        | Create item      |
```

**Ausrichtung:**

```markdown
| Links   | Zentriert | Rechts  |
|:--------|:---------:|--------:|
| Text    |   Text    |    Text |
```

---

## Listen

```markdown
<!-- Ungeordnet -->
- Kein Bloat
- Keine unnötigen Dependencies
  - Unterpunkt (2 Leerzeichen einrücken)

<!-- Geordnet -->
1. Repository klonen
2. Dependencies installieren
3. Server starten
```

---

## Zitate & Hinweise

```markdown
> A minimal REST API for user authentication and resource management.

> **Hinweis:** API läuft auf `http://localhost:8000`
```

---

## Horizontale Linie

```markdown
---
```

---

## Checkboxen (GitHub Task Lists)

```markdown
- [x] Repository erstellt
- [x] README.md hinzugefügt
- [ ] CI/CD konfiguriert
- [ ] Tests geschrieben
```

---

## Komplette README-Struktur (Vorlage)

```markdown
# Projektname

**Kurzbeschreibung in einem Satz**

![Badge](https://img.shields.io/badge/...)

---

Ausführlichere Beschreibung des Projekts.

## Installation

```bash
git clone https://github.com/user/repo.git
cd repo
pip install -r requirements.txt
```

## Verwendung

Beschreibung der Nutzung.

## Endpoints / API

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /        | Startseite  |

## Lizenz

MIT
```

---

## Nützliche GitHub-spezifische Syntax

```markdown
<!-- Kommentar (unsichtbar im gerenderten Dokument) -->

<details>
<summary>Klick mich</summary>

Versteckter Inhalt hier.

</details>
```

---

*Erstellt mit Claude AI · Projekt: markdownexample*
