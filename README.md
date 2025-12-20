Data Pipeline – FDA Drug Recalls (Showcase)
Ce dépôt présente les résultats, visualisations et livrables finaux d’un projet de data engineering complet basé sur les données de rappels de médicaments de la FDA (OpenFDA).

Le code source complet (pipeline, orchestration, infrastructure) est maintenu dans un dépôt privé et peut être partagé lors d’entretiens techniques.

🎯 Objectif du projet
Construire un pipeline de données scalable, fiable et industrialisable permettant :

l’ingestion continue de données OpenFDA,
leur transformation selon une architecture Medallion (Bronze → Silver → Gold),
l’exposition de KPIs métier via des dashboards.
📊 Ce que contient ce dépôt (PUBLIC)
✔️ Captures de dashboards
✔️ Résultats analytiques finaux
✔️ KPIs agrégés
✔️ Exemples d’outputs (anonymisés)
✔️ Documentation fonctionnelle haut niveau

❌ Aucun code source
❌ Aucun secret ou fichier de configuration
❌ Aucun pipeline exécutable

🏗️ Architecture – Vue Haut Niveau
OpenFDA API
    ↓
Ingestion & Streaming
    ↓
Bronze (Raw data)
    ↓
Silver (Clean & validated)
    ↓
Gold (Analytics-ready)
    ↓
PostgreSQL
    ↓
Grafana Dashboards
Architecture inspirée des standards Data Platform / Lakehouse utilisés en environnement entreprise.

📈 Indicateurs clés exposés
Nombre total de rappels
Répartition par fabricant
Répartition par statut de rappel
Tendances temporelles
Évolution journalière des événements
(Voir dossiers screenshots/ et results/)

🖼️ Aperçu des résultats
Les dashboards Grafana et sorties analytiques sont disponibles dans :

screenshots/
results/metrics/
results/images/
Ces éléments représentent l’état final du pipeline après orchestration et traitements.

🔒 Accès au code source
L’implémentation complète (Kafka, Spark, Airflow, MinIO, PostgreSQL, Docker) est volontairement conservée dans un dépôt privé.

📌 Le code peut être partagé sur demande, dans un contexte d’entretien ou d’évaluation technique.

🧠 Compétences démontrées
Data Engineering end-to-end
Architecture Medallion (Bronze / Silver / Gold)
Streaming & Batch processing
Orchestration de pipelines
Modélisation analytique
Monitoring & observabilité
Environnements containerisés
📅 Contexte
Projet développé dans une logique professionnelle et industrialisable, inspirée des architectures data modernes utilisées en entreprise.

👤 Auteur
Développé par l’équipe Data
📍 France
📅 2025
