# Croissance de *Paracentrotus lividus* Lamarck (1816)

## Avant-propos

Cette séance d’exercices est susceptible d'évoluer. N’hésitez pas à vérifier le lien suivant afin de voir si des modifications n’ont pas été apportées dans les consignes : <https://github.com/BioDataScience-Course/B02Ga_urchin>

## Objectifs

Ce projet est un travail en binôme à réaliser sur plusieurs modules. Vous allez devoir compléter les fichiers qui se trouvent dans le dossier `docs` : 

- **urchin_notebook.Rmd** qui se trouve dans `docs/urchin_notebook.Rmd`
- **urchin_report.Rmd** qui se trouve dans `docs/urchin_report.Rmd`

Réalisez un **carnet de notes** (notebook) afin d'explorer librement les données relatives à la biométrie de l'oursin violet. Réalisez des régressions linéaires simples, multiples et polynomiales et des modèles linéaires pour étudier ces données.

## Mise en situation

Les données employées dans le cadre de cette étude proviennent de recherches portant sur la croissance de *Paracentrotus lividus* Lamarck (1816) en élevage, comparées à d'autres mesures effectuées sur des animaux issus de la même population d'origine, mais ayant grandi en milieu naturel (à Morgat en Bretagne). Vous pouvez importer les données via la fonction suivante :

```
SciViews::R
urchin <- read("urchin_bio", package = "data.io")
```

N'hésitez pas à faire appel à la page d'aide de ce jeu de données :

```
.?urchin_bio
```

## Module 2

À la fin de ce module, vous devez avoir complété les sections relatives à la régression linéaire, à la régression linéaire multiple et à la régression linéaire polynomiale de votre notebook. Afin de comprendre le contexte, vous trouverez dans la section `biblio` une publication qui utilise ces données.

## Module 3

A la fin de ce module, vous devez avoir complété les sections relatives au modèle linéaire de votre notebook. Vous devez également réaliser le rapport. Votre rapport sera la synthèse de votre notebook/ Il en reprendra les éléments importants, c'est-à-dire, ceux que vous retenez de votre étude (là où le notebook reprend **tous** les essais que vous avez réalisés sur `urchin`). Inspirez-vous de la pulbication dans le dossier `biblio` pour écrire les quelques phrases de l'introduction et de la section matériel et méthodes du rapport.


## Note

_Veuillez toujours en fin de travail à ce que vos documents Rmd compilent bien sans erreurs en documents HTML via le bouton **Knit**. En cas d'erreur, résolvez-les. Des documants qui ne compilent pas ne sont pas recevables._
