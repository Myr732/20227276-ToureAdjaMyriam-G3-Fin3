# Références — Projet F3 : Prévision de l'inflation

## 1. Indice des prix à la consommation — CPIAUCSL

- **Organisme producteur :** U.S. Bureau of Labor Statistics (BLS)
- **Plateforme :** Federal Reserve Economic Data (FRED)
- **Série :** CPIAUCSL
- **Description :** Indice des prix à la consommation américain, corrigé des variations saisonnières.
- **Fréquence :** Mensuelle
- **Lien :** https://fred.stlouisfed.org/series/CPIAUCSL
- **Date d'extraction :** 25/11/26
- **Fichier :** `data/raw/CPIAUCSL.csv`

## 2. Taux de chômage — UNRATE

- **Organisme producteur :** U.S. Bureau of Labor Statistics (BLS)
- **Plateforme :** Federal Reserve Economic Data (FRED)
- **Série :** UNRATE
- **Description :** Taux de chômage aux États-Unis, corrigé des variations saisonnières.
- **Fréquence :** Mensuelle
- **Unité :** Pourcentage
- **Lien :** https://fred.stlouisfed.org/series/UNRATE
- **Date d'extraction :** 25/11/26
- **Fichier :** `data/raw/UNRATE.csv`

## 3. Taux des fonds fédéraux — FEDFUNDS

- **Organisme producteur :** Board of Governors of the Federal Reserve System
- **Plateforme :** Federal Reserve Economic Data (FRED)
- **Série :** FEDFUNDS
- **Description :** Taux d'intérêt effectif des fonds fédéraux américains.
- **Fréquence :** Mensuelle
- **Unité :** Pourcentage
- **Lien :** https://fred.stlouisfed.org/series/FEDFUNDS
- **Date d'extraction :** 25/11/26
- **Fichier :** `data/raw/FEDFUNDS.csv`

## 4. Utilisation des données

Les trois séries seront utilisées pour étudier si le taux de chômage et le taux des fonds fédéraux permettent d'améliorer la prévision de l'inflation américaine.

Le taux d'inflation annuel sera calculé à partir de l'indice CPIAUCSL pendant l'épreuve.

## 5. Limites des données

Certaines séries économiques peuvent être révisées après leur première publication. Les données téléchargées peuvent donc être différentes de celles effectivement disponibles aux dates historiques étudiées.

Cette limite devra être prise en compte dans l'interprétation des résultats.
