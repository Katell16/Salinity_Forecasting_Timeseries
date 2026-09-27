# Prévision de la salinité de la rivière Thu-Bồn

Projet réalisé dans le cadre d'un stage de fin d'études (avril – août 2026, Vietnam), mené en anglais au sein d'une équipe de recherche internationale.

## Objectif

Prédire l'évolution de la salinité de la rivière Thu-Bồn à partir de données hydrologiques, afin d'anticiper les intrusions salines pour l'irrigation agricole ainsi que pour l'approvisionnement en eau potable.

## Données

- Source : station de Cau Do (niveau d'eau de la rivière, marée, salinité), station de Hoi An et de Cau Lau, débit des barrages de Thanh My et Nong Son
- Variables : débit, niveau d'eau, marée, salinité historique
- Fréquence : pas de 15min

## Méthodologie

- Prétraitement et nettoyage des données sous Python (pandas)
- Analyse exploratoire des séries temporelles
- Modélisation prédictive : XGBoost, LSTM, CNN
- Évaluation des performances : RMSE, MAE, R²

## Outils utilisés

Python · pandas · scikit-learn · tensorflow · numpy ...

## Note

Ce dépôt présente une version anonymisée/simplifiée du projet, les données brutes et certains éléments méthodologiques restant confidentiels dans le cadre du stage.
