---
layout: post
title:  "Compte rendu de la réunion du 02/06/2016"
---

# Compte rendu reunion 02.06.2017


# Todo

- [ ] clusters qui n'existent pas ?
- [ ] doc en anglais
- [ ] convergent-divergent
- [ ] test unitaires
- [ ] optimiser le code

# A voir après
- [ ] utiliser dbscan pour générer les données
- [ ] mise en place du workflow à partir de movebank

# A consulter
- [ ] movebank data repository
- [ ] explications des algos lcm : http://fimi.ua.ac.be/src/
- [ ] sources implementations lcm : http://ceur-ws.org/Vol-90/uno.pdf
- [ ] leaflet.js

# Notions abordées

## Fonctionnement de GetMove

generateClusters -> remappe les données en entrée en matrice qui peut être exploitée par generatePattern
  - génère par rapport aux blocs les matrices des fichiers en entrée
  - obtenir les itemsets
  - création d'une matrice pour lcm
