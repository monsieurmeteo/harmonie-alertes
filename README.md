# harmonie-alertes

Carte de vigilance météo 48h non officielle (11 aléas, J/J+1, échelle propre à chaque aléa) — reproduction à l'identique de https://alertes-meteo.com/cartes-meteo/harmonie-alertes/.

- Données : `https://raw.githubusercontent.com/monsieurmeteo/risques/data/risques.json` (pipeline GitHub Actions `risques` de monsieurmeteo, seuils identiques à la production).
- Modèle source : HARMONIE-AROME Cy43 (KNMI), CC BY 4.0 — pipeline `monsieurmeteo/harmonie`.
- Code du widget : plugin open source GPL-2.0-or-later (Alertes Météo Hub).
