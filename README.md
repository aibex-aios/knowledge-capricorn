# knowledge-capricorn

Wissenspaket von AIbex AIOS, Version 0.1.0: die Regel Capricorn. Jede Antwort der KI beginnt mit dem Präfix „🐐 “, der User wird mit Du angeredet. Die Regel liegt in `knowledge/@Rule/Capricorn/Capricorn.md` und wird nach dem Holen geladen, als läge sie in `@/@Rule/` des Masterspace (Spec 02, K6).

Ein zugeordneter Assistent mit eigenem Präfix (z. B. Anja) überschreibt das Präfix der Regel; das ist gewollt.

## Voraussetzung

AIOS v0.6.2 oder neuer (v0.6), Vault an AIOS gebunden.

## Holen

```bash
aios --fetch knowledge-capricorn
```

Teil der Distribution `distribution-capricorn` ab 0.5.0.

## Lizenz

CC-BY-4.0
