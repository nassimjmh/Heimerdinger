
##### Projet numérique physique moderne
##### Hicham El Jarjini, Kentaro Loret, Nassim Jamhour
---

# Simulation de la mécanique quantique : puits de potentiel et états stationnaires

Ce projet Python permet de simuler et visualiser l'évolution d'une particule quantique dans un puits de potentiel, en utilisant une approche numérique basée sur l'équation de Schrödinger dépendante du temps. Il permet également d'afficher les **états stationnaires** associés à ce système quantique.

## Fonctionnalités principales

* **Simulation de la propagation temporelle d'une onde quantique** dans un puits de potentiel rectangulaire.
* **Animation de la densité de probabilité** au cours du temps (sous forme d’un fichier `.gif`).
* **Calcul et affichage des états stationnaires** du système, en fonction du potentiel défini.
* Interface en ligne de commande pour définir les paramètres personnalisés : pas spatial/temps, largeur du paquet, profondeur du puits, énergie relative, etc.

## Dépendances

```bash
numpy
matplotlib
scipy
```

## Exécution

```bash
python etat_stationnaire.py
```

## Fichiers générés

* `data/animation.gif` : animation de l'évolution de la densité de probabilité.
* `data/etats_stationnaires.png` : graphique des premiers états stationnaires (si demandé à la fin de l'exécution).


---

