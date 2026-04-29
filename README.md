# Site Sacha TERRAT — v11

Correction des logos partenaires.

## Fichiers à remplacer
- `src/layouts/Base.astro`
- `src/pages/booking.astro`
- `src/pages/projets.astro`

## Ce qui change
- ❌ Logo "Co-funded by EU" retiré
- ❌ Logo DRAC retiré, remplacé par texte "Soutenu par la DRAC Île-de-France"
- ✅ Logos KeyChange + MJC Chaville conservés avec fond blanc pour lisibilité
- ✅ Suppression du filtre `brightness(0) invert(1)` qui écrasait les logos
- ✅ Fallback robuste via `onerror` inline (compatible tous navigateurs)

## Logos requis dans `/public/images/logos/`
- `keychange.png`
- `mjc-chaville.png`

Si l'un manque : un placeholder en typo s'affiche automatiquement.
