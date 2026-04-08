# À Propos
[cite_start]Je suis **Géographe-Écologue** [cite: 3][cite_start], passionné par l'étude des écosystèmes forestiers tropicaux[cite: 3]. [cite_start]Mon expertise réside dans l'application de l'analyse de données spatiales et statistiques [cite: 3] [cite_start]pour comprendre l'impact des changements globaux sur la biodiversité[cite: 3]. 

[cite_start]Basé à Parakou, j'interviens comme consultant en **SIG** pour des études d'impact environnemental et des projets de gestion des ressources naturelles[cite: 44, 52, 60].

## Parcours Académique
* [cite_start]**Master (M1) Aménagement et Gestion des Ressources Naturelles** — Université de Parakou (2025-2026) [cite: 5, 6]
* [cite_start]**Licence Professionnelle en Géographie Physique** (Géomatique et Biodiversité) — Université de Parakou (2019-2022) [cite: 11, 12]

## Projets R & Cartographie
### Analyse spatiale : Résultats BAC Bénin 2025
Visualisation automatique des taux de réussite par département au Bénin à l'aide de R et ggplot2.

![Carte BAC 2025](carte_BAC_2025.jpg)

#### Aperçu du Script R
```r
library(ggplot2)
library(sf)
# Analyse spatiale du taux de réussite par département
bac_data <- data.frame(
  DEPARTEMENT = c("Alibori", "Atacora", "Atlantique"),
  TAUX = c(60.55, 65.54, 78.13)
)
