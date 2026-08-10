# Bloomanji — kit logo

## Fichiers
- `bloomanji-symbol.svg` — symbole seul, bicolore. Usage principal.
- `bloomanji-lockup.svg` — symbole + nom, horizontal. Header de site, signature mail.
- `bloomanji-symbol-mono.svg` — monochrome, utilise `currentColor` (hérite la couleur CSS du parent).
- `bloomanji-favicon.svg` — carré à coins arrondis, fond bleu nuit. Favicon et icône d'app.

## Palette
| Rôle | Hex |
|---|---|
| Bleu clair (pétales) | `#85B7EB` |
| Bleu principal (pétales) | `#378ADD` |
| Bleu appui (coeur, texte) | `#185FA5` |
| Bleu nuit (fond, texte) | `#0C447C` |

## Notes
- Le lockup utilise une police système en fallback. Pour figer le rendu, remplacer le `<text>` par des tracés vectorisés une fois la police définitive choisie.
- Le symbole reste lisible jusqu'à 16 px. Ne pas descendre le lockup sous 120 px de large.
- Zone de protection : laisser autour du symbole un espace égal au rayon d'un pétale.
