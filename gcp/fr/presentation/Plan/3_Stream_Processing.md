# 3. Analyse Approfondie : Traitement en Flux


## Caractéristiques :

- [ ] **Volume de Données :** Flux de données continus, non délimités et de petite taille.
- [ ] **Latence :** Faible latence (de la sous-seconde à quelques secondes).
- [ ] **Débit :** Peut gérer des données à haute vélocité.
- [ ] **Exécution :** Traitement continu et événementiel.

## Cas d'Usage Courants :

- [ ] Détection de fraude en temps réel dans les transactions financières.
- [ ] Surveillance et alerte des données de capteurs IoT.
- [ ] Tableaux de bord en direct pour les applications de jeux.
- [ ] Analyse des clics (clickstream) pour les sites web et les applications mobiles.

## Services Google Cloud Clés pour le Traitement en Flux :

- [ ] **Pub/Sub :** Pour l'ingestion et le stockage de flux de données en temps réel.
- [ ] **Dataflow :** Pour charger, transformer et traiter les données en flux.
- [ ] **Google Cloud Functions :** Calcul sans serveur et événementiel pour le traitement d'événements individuels.
- [ ] **Services Kafka gérés (par ex., Confluent Cloud) :** Pour les workflows Kafka gérés.
- [ ] **Dataproc :** Pour exécuter Spark Streaming ou Flink sur un cluster géré.

## Avantages et Inconvénients :

  - [ ] **Avantages :** Informations en temps réel, réponse immédiate aux événements, hautement scalable.
  - [ ] **Inconvénients :** Peut être plus complexe à concevoir et à gérer, coûts opérationnels potentiellement plus élevés, nécessite la gestion des données désordonnées.