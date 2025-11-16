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

## Services Azure Clés pour le Traitement par Lots :

- [ ] **Azure Blob Storage :** Stockage de lac de données (data lake) pour les données brutes et traitées.
- [ ] **Azure Data Factory :** Service ETL sans serveur pour la préparation et le chargement des données.
- [ ] **Azure HDInsight & Azure Synapse Analytics :** Plateformes de big data gérées (Spark, Hadoop, Hive).
- [ ] **Azure Batch :** Service de calcul par lots entièrement géré pour la planification et l'exécution des tâches.
- [ ] **Azure Synapse Analytics :** Entrepôt de données (data warehouse) pour l'analyse à grande échelle.

## Avantages et Inconvénients :

- [ ] **Avantages :** Rentable pour les grands ensembles de données, débit élevé, architecture simple.
- [ ] **Inconvénients :** Latence élevée, les informations ne sont pas en temps réel, peut être complexe à gérer pour les requêtes ad-hoc.