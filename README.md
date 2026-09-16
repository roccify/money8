# Zaslužek dashboard

Astro + Tailwind CSS dashboard za tekoči prikaz zaslužka.

## Vključeno

- tekoči zaslužek v trenutni uri
- tekoči dnevni zaslužek
- zaslužek v tekočem mesecu
- zaslužek od začetka leta
- trenutna ura in datum
- slovensko formatiranje zneskov z obveznim ločilom tisočic
- responsive postavitev za desktop in mobile

## Lokalni zagon

```bash
npm install
npm run dev
```

## Produkcijski build

```bash
npm run build
```

Build se ustvari v mapi `dist/`.

## Struktura

- `src/pages/index.astro` - stran, izračuni in komponentni CSS
- `src/styles/global.css` - globalni stil in Tailwind import
- `astro.config.mjs` - Astro + Tailwind Vite konfiguracija
- `package.json` - odvisnosti in npm ukazi
- `.gitignore` - datoteke, ki se ne nalagajo v Git


## V7
Kompaktnejša premium postavitev s tremi karticami. Vsi zneski imajo enako velikost pisave; kartice so nižje, postavljene višje, naslovi so subtilnejši, dekorativne črte krajše in YTD poudarek bolj diskreten.
