# konverze-scoop — Scoop bucket pro Konverzi

Instalace **[Konverze](https://konverze.pravnikovo.info)** (autorizovaná konverze
dokumentů, I.CA / PostSignum, Czech POINT) na Windows přes [Scoop](https://scoop.sh)
— bez SmartScreen varování z prohlížeče.

```powershell
scoop bucket add konverze https://github.com/pravnikovo-info/konverze-scoop
scoop install konverze
```

Aktualizace: `scoop update konverze`

Manifest (`bucket/konverze.json`) obsahuje jen metadata — verzi, URL na veřejný
download a SHA-256. Žádný zdrojový kód. Aktualizuje se automaticky při každém
vydání (`release.sh` v hlavním repu).
