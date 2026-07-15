# ADR-001: Storage-Substrat

## Status

Akzeptiert.

## Kontext

Wir brauchen ein Substrat, das Redeploys und Cold-Starts übersteht.

## Entscheidung

| Option      | Durabel           | Gewählt |
| ----------- | ----------------- | ------- |
| Dateisystem | nur Einzelinstanz | nein    |
| Azure Blob  | ja                | ja      |

## Konsequenzen

> Der Blob-Store trägt Multi-Instance; der Reconciler baut darauf auf.
