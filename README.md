# Boussole Avenir en commun

Mini app pour parcourir les 795 mesures de la version synthétique de *L'Avenir en commun* (programme 2027 porté par Jean-Luc Mélenchon), les trier pour/contre en swipant et voir son alignement thème par thème.

**➡️ Ouvrir l'app : https://inseikei.github.io/boussole-avenir-en-commun/**

## Fonctionnalités
- **Deux versions** : complète (795 mesures) ou courte (69 mesures à impact 3, les plus structurantes). Lien direct vers la version courte : https://inseikei.github.io/boussole-avenir-en-commun/?version=courte
- **Trier** : swipe pour / contre / neutre, filtres par chapitre et profil (salarié, retraité, jeune, locataire, parent, indépendant), tri par impact potentiel.
- **Explorer** : recherche, filtres, favoris et notes personnelles.
- **Bilan** : alignement global et score par thème (option pondérée par l'impact).

Tes votes et notes restent dans ton navigateur (localStorage) : rien n'est envoyé nulle part.

## Design
Interface construite avec le système **Repères** (palette Océan, police Source Sans 3 sous licence SIL Open Font License, fichiers dans `fonts/`).

## Sources et limites
- Chaque mesure est **reformulée en une ligne** ; le lien « Original » renvoie au texte complet sur [lavenirencommun.org](https://www.lavenirencommun.org/) (site non officiel). Programme officiel : [melenchon2027.fr](https://melenchon2027.fr/).
- Le **score d'impact (1–3)** est une estimation de l'ampleur d'une mesure (population touchée, poids budgétaire ou institutionnel), pas un jugement sur sa pertinence.
- Projet personnel, non affilié à La France insoumise ni à la campagne.
