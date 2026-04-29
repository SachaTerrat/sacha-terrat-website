# 📁 Dossier Logos

Place ici les fichiers logos de tes partenaires institutionnels.

## Fichiers attendus (noms exacts)

- `keychange.png` — Logo KeyChange
- `drac-idf.png` — Logo DRAC Île-de-France
- `mjc-chaville.png` — Logo MJC de Chaville (25 de la Vallée)
- `eu-cofunded.png` — Logo "Co-funded by the European Union"

## Format recommandé

- **PNG avec fond transparent**
- Hauteur ~100-200px
- Poids <50 Ko par fichier

## Si un logo n'est pas placé

Aucun souci — le site affichera un placeholder élégant en typo à la place.
Tu peux donc placer les logos progressivement.

## Astuce

Le CSS du site applique automatiquement un filtre qui rend les logos **en blanc**
(parce que le site est sombre). Donc même un logo noir basique fonctionnera bien.

Pour conserver les couleurs d'origine d'un logo, tu peux modifier le CSS dans
`src/layouts/Base.astro` (chercher `filter: brightness(0) invert(1)` et le commenter).
