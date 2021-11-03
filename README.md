# Croissance de *Parocentrotus lividus* Lamarck (1816)

## Avant-propos

Cette séance d’exercices est susceptible d'évoluer. N’hésitez pas à vérifier le lien suivant afin de voir si des modifications n’ont pas été apportées dans les consignes : <https://github.com/BioDataScience-Course/B02G_urchin>

## Objectifs

Ce projet est un travail en binôme à réaliser sur plusieurs modules. Vous allez devoir compléter les fichiers qui se trouvent dans le dossier docs : 

- **urchin_notebook.Rmd** qui se trouve dans `docs/urchin_notebook.Rmd`
- **urchin_report.Rmd** qui se trouve dans `docs/urchin_report.Rmd`

Réalisez un carnet de laboratoire afin d'explorer les données sur la biométrie des oursins. Réalisez des régressions linéaires simples, multiples et polynomiales et des modèles linéaires pour étudier les données.

## Mise en situation

Les données employées dans le cadre de cette étude proviennent de recherches portant sur la croissance de *Paracentrotus lividus* Lamarck (1816) en élevage. Vous pouvez importer les données via la fonctions suivantes :

```
SciViews::R
urchin <- read("urchin_bio", package = "data.io")
```

N'hésitez pas à faire appel à la page d'aide de ce jeu de données

```
.?urchin_bio
```

## Module 2

A la fin de ce module, vous devez avoir complété les sections relative à la régression linéaire, à la régression linéaire multiple et à la régression linéaire polynomiale de votre notebook. Afin de comprendre le contexte, vous trouverez dans la section `biblio` une pulbication relative à ces données. Inspirez-vous en pour écrire les quelques phrases de l'introduction et de la section matériel et méthodes du rapport.

## Module 3

A la fin de ce module, vous devez avoir complété les sections relative au modèle linéaire de votre notebook. Vous devez également réaliser le rapport. Votre rapport seravla synthèse de votre notebook et en reprend les éléments importants que vous retenez de votre étude (là où le notebook reprend **tous** les essais que vous avez réalisés sur `urchin`.

