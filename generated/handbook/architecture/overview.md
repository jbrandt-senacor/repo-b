Diese Übersicht ist eine redaktionelle Einleitung ohne eigene Quelle.

# Architektur-Übersicht

Die Wissensbasis trennt **generierte** von **menschlichen** Seiten.

> Git ist die Quelle der Wahrheit; die App bezeugt, sie ersetzt nicht.

## Namensräume

- `generated/**` — vom Generator geschrieben, provenienzbelegt
- `human-authored/**` — von Menschen gepflegt

---

## Datenfluss

Repo A wird gelesen, normalisiert und als ein atomarer Commit nach Repo B
geschrieben.

![Datenfluss-Diagramm](https://example.com/diagrams/flow.png)
