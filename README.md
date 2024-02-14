

# CollabScore data/metadata

## Métadonnées

- [data/collabscore-saintsaens.json](data/collabscore-saintsaens.json): Métadonnées corpus de référence Saint-Saëns

Fichier complété et maintenu 'humainement', avec en particulier des métadonnées sur les oeuvres, mais aussi sur les encodeurs, les éditions et enfin les interprètes des fichiers audios. Côté Dezrann, ces métadonnées sont notamment utilisées pour compléter ce qui est disponible sur Neuma et notamment afficher la [page du corpus Collabscore](http://dezrann.net/explore/collabscore).

Le format est décrit dans [metadata-piece.md](https://gitlab.com/algomus.fr/dezrann/dezrann-corpus/-/blob/main/doc/metadata-piece.md). Il peut y avoir plus ou moins d'information suivant les pièces. La première pièce a des sources `score` et `score:gallica`, mais c'est optionnel: les autres pièces ont simplement `score:neuma`, et tout est récupéré à partir de Neuma.

