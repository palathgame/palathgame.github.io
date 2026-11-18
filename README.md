# filiplukes.github.io

Web vývojáře PalathGame na GitHub Pages: https://filiplukes.github.io

- `app-ads.txt`: ověření AdMob. Musí zůstat přímo v kořeni repozitáře.
- `index.html`: seznam her.
- `privacy/index.html`: zásady ochrany osobních údajů pro všechny hry
  (URL pro Google Play: https://filiplukes.github.io/privacy/).

## Nová hra

1. Obrázky (ikona cca 256 px, pozadí cca 1280 px na šířku) dej do `images/`.
2. V `index.html` zkopíruj blok `<article class="game">` a uprav texty, obrázky a odkaz na obchod.
3. V `privacy/index.html` přidej sekci hry (vlastní `id`) se službami, které hra používá.
4. Má-li hra jiný AdMob účet, přidej jeho řádek do `app-ads.txt`.
5. Commit a push. Web se aktualizuje během pár minut.
