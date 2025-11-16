# 5. Architectures Hybrides : Le Meilleur des Deux Mondes


## Architecture Lambda :

  - [ ] Combine une couche de lots (batch layer) pour des vues complètes et précises et une couche de vitesse (speed layer) pour les données en temps réel.
  - [ ] **Composants :** Couche de Lots, Couche de Vitesse, Couche de Service.
  - [ ] **Avantages :** Tolérante aux pannes, fournit des vues en temps réel et historiques.
  - [ ] **Inconvénients :** Grande complexité, logique redondante entre les couches.

## Architecture Kappa :

- [ ] Une approche simplifiée qui traite tout comme un flux.
- [ ] **Composants :** Un seul pipeline de traitement de flux qui gère à la fois le retraitement des données en temps réel et historiques.
- [ ] **Avantages :** Architecture simplifiée, moins de duplication de code.
- [ ] **Inconvénients :** Le retraitement de grands ensembles de données historiques peut être difficile.
