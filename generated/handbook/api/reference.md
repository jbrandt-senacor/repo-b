# API-Referenz

Alle Endpunkte liegen unter `/api/v1/wiki`.

## Seiten lesen

```http
GET /api/v1/wiki/page/:id
```

Antwortet mit dem Read-DTO der Seite.

## Fehlercodes

| Code                  | Bedeutung                   |
| --------------------- | --------------------------- |
| `PAGE_CONFLICT`       | Seite wurde gerade geändert |
| `COMMONS_UNAVAILABLE` | Commons nicht verdrahtet    |
