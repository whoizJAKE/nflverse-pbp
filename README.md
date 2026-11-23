# nflverse pbp data

French below

[![Update PBP Related Data](https://github.com/nflverse/nflverse-pbp/actions/workflows/update_data.yaml/badge.svg)](https://github.com/nflverse/nflverse-pbp/actions/workflows/update_data.yaml)

This repository stores code and workflows for updating nflverse play by play, player stats, and kicking stat summaries. The data itself is now being automatically pushed to GitHub releases at https://github.com/nflverse/nflverse-data/releases, which reduces repository bloat. 


For more on why we use releases, see [Tan's talk  at rstudio::conf(2022).](https://github.com/tanho63/project_immortality)

We recommend using the [`nflreadr` R package](https://nflreadr.nflverse.com) to access the latest data or [`nfl-data-py` for Python](https://pypi.org/project/nfl-data-py/). If you would like to read directly from URLs, linking to nflverse-data release URLs is now the best way to do so. 

Data here will eventually be archived away from this repository (by August 2022) and we encourage everyone to shift to nflverse-data URLs for all projects. 

nflreadr v1.2.0+ will correctly reference files for these changes.

// Partie en Français //


Ce dépôt contient le code et les flux de travail permettant de mettre à jour les données « play-by-play » (action par action), les statistiques des joueurs et les résumés des statistiques de coups de pied (kicking stats) pour nflverse. Les données elles-mêmes sont désormais automatiquement publiées via la fonctionnalité « Releases » de GitHub, à l'adresse https://github.com/nflverse/nflverse-data/releases, ce qui permet d'alléger le dépôt.

Pour en savoir plus sur les raisons pour lesquelles nous utilisons les « Releases », vous pouvez consulter la présentation de Tan lors de la conférence rstudio::conf(2022).

Nous recommandons d'utiliser le package R `nflreadr` — ou `nfl-data-py` pour Python — afin d'accéder aux données les plus récentes. Si vous préférez charger les données directement depuis des URL, utiliser les liens vers les « Releases » de `nflverse-data` constitue désormais la méthode privilégiée.

À terme (d'ici août 2022), les données présentes ici seront archivées en dehors de ce dépôt ; nous encourageons donc tous les utilisateurs à adopter les URL de `nflverse-data` pour leurs projets.

La version 1.2.0 (ou supérieure) de `nflreadr` prendra en compte ces changements et pointera correctement vers les fichiers concernés.
