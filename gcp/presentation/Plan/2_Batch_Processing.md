# 2. Analyse Approfondie : Traitement par Lots


## Caractéristiques :

- [ ] **Volume de Données :** Ensembles de données volumineux et délimités.
- [ ] **Latence :** Latence élevée (minutes à heures).
- [ ] **Débit :** Un débit élevé est un objectif principal.
- [ ] **Exécution :** Tâches planifiées et périodiques.

## Cas d'Usage Courants :

- [ ] Rapports et analyses de fin de journée.
- [ ] Systèmes de paie et de facturation.
- [ ] Tâches ETL (Extraire, Transformer, Charger) à grande échelle.
- [ ] Séquençage génomique.

## Services Google Cloud Clés pour le Traitement par Lots :

- [ ] **Google Cloud Storage :** Stockage de lac de données (data lake) pour les données brutes et traitées.
- [ ] **Cloud Data Fusion & Dataproc :** Service ETL sans serveur et Spark/Hadoop géré pour la préparation et le chargement des données.
- [ ] **Dataproc :** Plateforme de big data gérée (Spark, Hadoop, Hive).
- [ ] **Google Cloud Batch :** Service de calcul par lots entièrement géré pour la planification et l'exécution des tâches.
- [ ] **BigQuery :** Entrepôt de données (data warehouse) pour l'analyse à grande échelle.

## Avantages et Inconvénients :

- [ ] **Avantages :** Rentable pour les grands ensembles de données, débit élevé, architecture simple.
- [ ] **Inconvénients :** Latence élevée, les informations ne sont pas en temps réel, peut être complexe à gérer pour les requêtes ad-hoc.