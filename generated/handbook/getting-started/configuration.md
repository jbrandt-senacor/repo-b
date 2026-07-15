# Konfiguration

Die Anwendung liest ihre Einstellungen aus Umgebungsvariablen.

## Variablen

| Variable        | Pflicht | Bedeutung                     |
| --------------- | ------- | ----------------------------- |
| `STORE_BACKEND` | nein    | `blob` oder Datei-Default     |
| `DATA_DIR`      | ja      | persistentes Datenverzeichnis |
| `PLATFORM_AUTH` | nein    | `easy-auth` aktiviert Entra   |

## Hinweise

Siehe die [offizielle Node-Doku][node] für Versionsanforderungen.

[node]: https://nodejs.org/en/about/releases
