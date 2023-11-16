# Applied Econometrics Projects

## Introduction
Ce dossier contient mes projets en économétrie : "Emissions-GES" et "Sexual Violence". Ces projets visent à appliquer des techniques économétriques pour analyser des phénomènes spécifiques, allant des émissions de gaz à effet de serre à l'étude des violences sexuelles.

## Emissions-GES Project

L'objectif principal de ce projet est d'analyser les émissions de gaz à effet de serre (GES) et d'identifier les facteurs qui influent sur ces émissions.

## Sexual Violence Project

Ce projet vise à étudier les violences sexuelles en France par département en utilisant des méthodes économétriques.

## Exécution des Projets
Assurez-vous d'avoir créé et activé votre environnement virtuel.
   ```bash
   install.packages("renv")
   renv::init()
   pacman::p_load(car, lmtest, sandwich, stargazer, broom, dplyr, ggplot2, plm, tseries, urca, zoo)
