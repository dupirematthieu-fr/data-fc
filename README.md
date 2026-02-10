⚽ DATA FC – Football Investment Decision Tool
DATA FC est un outil d’aide à la décision basé sur l’analyse de données footballistiques et financières, développé avec Google BigQuery.

L’objectif est d’accompagner de futurs investisseurs dans le choix d’un club de football professionnel correspondant à leurs attentes sportives, économiques et stratégiques.

🎯 Objectif du projet
Le rachat d’un club de football représente un investissement complexe et à fort enjeu.
DATA FC vise à objectiver ce choix en consolidant plusieurs dimensions clés :

Performance sportive
Valeur économique du club
Attractivité du stade
Potentiel de croissance
Grâce à des indicateurs clairs et comparables, l’outil permet d’identifier les clubs les plus alignés avec un profil d’investisseur donné.

Pour ce projet nous avons utilisé:

BigQuery -> Stockage de données, modeling et transformations
Looker Studio -> Dashboard final
Différentes sources -> Scraping depuis différents sites internet tels que transfermarkt et database provenant de kaggle (sources publiques)
📊 Données analysées
Les analyses reposent sur des ensembles de données structurés autour de :

Valeur marchande des clubs
Affluence moyenne au stade
Propriété du stade (club propriétaire ou non)
Championnat et niveau de compétition
Évolution des indicateurs clés dans le temps
Les données présentes dans ce repository sont anonymisées ou issues de sources publiques.

🧱 Approche & méthodologie
Le projet repose sur une modélisation simple et lisible des données réalisée sur BigQuery:

Sources → Modélisation → Indicateurs → Tables décisionnelles

Étapes principales :
Centralisation des données dans BigQuery
Nettoyage et harmonisation des formats
Création d’indicateurs business
Production de tables finales prêtes à l’analyse ou à la visualisation
📂 Contenu du repository
├── sql/ | ├── 01_sources.sql # Préparation des données sources | ├── 02_modelisation.sql # Structuration et relations | ├── 03_indicateurs_cles.sql # KPIs business | └── 04_tables_finales.sql # Tables décisionnelles

📊 Extraits du Dashboard (Looker Studio)
Capture d'écran 2026-02-03 200641 Capture d'écran 2026-02-03 200658 Capture d'écran 2026-02-03 200715 Capture d'écran 2026-02-03 200737 Capture d'écran 2026-02-03 200751 Capture d'écran 2026-02-03 200810 Capture d'écran 2026-02-03 200821
📈 Exemples d’indicateurs produits
Classement des clubs par attractivité globale
Comparaison valeur sportive vs valeur économique
Identification de clubs à fort potentiel de croissance
Analyse de la dépendance aux revenus de billetterie
💡 Cas d’usage
Investisseur privé souhaitant acquérir un club
Fonds d’investissement sportif
Cabinets de conseil spécialisés sport & finance
Analyse comparative entre ligues européennes
🚀 Évolutions possibles
Ajout d’un scoring personnalisé par profil d’investisseur
Intégration de données salariales et contractuelles
Connexion à un dashboard Looker Studio
Automatisation du pipeline de données
👤 Auteur
Matthieu DUPIRE
Projet réalisé dans un objectif de portfolio data / business intelligence.

📎 N’hésitez pas à me contacter pour toute question ou collaboration.
