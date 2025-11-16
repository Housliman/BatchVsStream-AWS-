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

## Services AWS Clés pour le Traitement en Flux :

- [ ] **Amazon Kinesis :**
  - [ ] **Kinesis Data Streams :** Pour l'ingestion et le stockage de flux de données en temps réel.
  - [ ] **Kinesis Data Firehose :** Pour charger des données en flux dans des entrepôts de données.
  - [ ] **Kinesis Data Analytics :** Pour traiter les flux avec SQL ou Apache Flink.

- [ ] **AWS Lambda :** Calcul sans serveur et événementiel pour le traitement d'événements individuels.

- [ ] **Amazon Managed Streaming for Apache Kafka (MSK) :** Service Kafka entièrement géré.

- [ ] **Amazon EMR :** Pour exécuter Spark Streaming ou Flink sur un cluster géré.

## Avantages et Inconvénients :

  - [ ] **Avantages :** Informations en temps réel, réponse immédiate aux événements, hautement scalable.
  - [ ] **Inconvénients :** Peut être plus complexe à concevoir et à gérer, coûts opérationnels potentiellement plus élevés, nécessite la gestion des données désordonnées.
