# ⚽ DATA FC – Football Investment Decision Tool

**DATA FC** est un outil d’aide à la décision basé sur l’analyse de données footballistiques et financières, développé avec **Google BigQuery**.

L’objectif est d’accompagner de futurs investisseurs dans le choix d’un club de football professionnel correspondant à leurs **attentes sportives, économiques et stratégiques**.

---

## 🎯 Objectif du projet

Le rachat d’un club de football représente un investissement complexe et à fort enjeu.  
DATA FC vise à **objectiver ce choix** en consolidant plusieurs dimensions clés :

- Performance sportive
- Valeur économique du club
- Attractivité du stade
- Potentiel de croissance

Grâce à des indicateurs clairs et comparables, l’outil permet d’identifier les clubs les plus alignés avec un profil d’investisseur donné.

Pour ce projet nous avons utilisé:
  - BigQuery -> Stockage de données, modeling et transformations
  - Looker Studio -> Dashboard final
  - Différentes sources -> Scraping depuis différents sites internet tels que transfermarkt et database provenant de kaggle (sources publiques)

---

## 📊 Données analysées

Les analyses reposent sur des ensembles de données structurés autour de :

- Valeur marchande des clubs
- Affluence moyenne au stade
- Propriété du stade (club propriétaire ou non)
- Championnat et niveau de compétition
- Évolution des indicateurs clés dans le temps

> Les données présentes dans ce repository sont anonymisées ou issues de sources publiques.

---

## 🧱 Approche & méthodologie

Le projet repose sur une modélisation simple et lisible des données réalisée sur BigQuery:

Sources → Modélisation → Indicateurs → Tables décisionnelles


### Étapes principales :
1. Centralisation des données dans BigQuery
2. Nettoyage et harmonisation des formats
3. Création d’indicateurs business
4. Production de tables finales prêtes à l’analyse ou à la visualisation

---

## 📂 Contenu du repository

├── sql/
|  ├── 01_sources.sql # Préparation des données sources
|  ├── 02_modelisation.sql # Structuration et relations
|  └── 03_tables_finales.sql # Tables décisionnelles


---

## 📊 Extraits du Dashboard (Looker Studio)

<img width="1441" height="1076" alt="Capture d&#39;écran 2026-02-03 200641" src="https://github.com/user-attachments/assets/dd7d99f6-d535-4f0d-887a-92ad44122922" />
<img width="1436" height="1077" alt="Capture d&#39;écran 2026-02-03 200658" src="https://github.com/user-attachments/assets/8eb3cce8-87ef-4218-a255-fb87eb3bcf88" />
<img width="1435" height="1077" alt="Capture d&#39;écran 2026-02-03 200715" src="https://github.com/user-attachments/assets/2937554b-38a6-46b1-ba63-0d7665cc2510" />
<img width="1435" height="1073" alt="Capture d&#39;écran 2026-02-03 200737" src="https://github.com/user-attachments/assets/ed6efd5a-1985-44a3-a9a2-04c68ae2fe48" />
<img width="1438" height="1074" alt="Capture d&#39;écran 2026-02-03 200751" src="https://github.com/user-attachments/assets/6022bd8a-828d-41ed-a9f0-471ef4770613" />
<img width="1439" height="1076" alt="Capture d&#39;écran 2026-02-03 200810" src="https://github.com/user-attachments/assets/258d771e-5fb0-4a87-9553-f3616117028a" />
<img width="1439" height="1076" alt="Capture d&#39;écran 2026-02-03 200821" src="https://github.com/user-attachments/assets/c9b17145-4b52-4d2e-931e-90aa91d58374" />

---

## 📈 Exemples d’indicateurs produits

- Classement des clubs par attractivité globale
- Comparaison valeur sportive vs valeur économique
- Identification de clubs à fort potentiel de croissance
- Analyse de la dépendance aux revenus de billetterie

---

## 💡 Cas d’usage

- Investisseur privé souhaitant acquérir un club
- Fonds d’investissement sportif
- Cabinets de conseil spécialisés sport & finance
- Analyse comparative entre ligues européennes

---

## 🚀 Évolutions possibles

- Ajout d’un scoring personnalisé par profil d’investisseur
- Intégration de données salariales et contractuelles
- Connexion à un dashboard Looker Studio
- Automatisation du pipeline de données

---

## 👤 Auteur

**Matthieu DUPIRE**  
Projet réalisé dans un objectif de **portfolio data / business intelligence**.

📎 N’hésitez pas à me contacter pour toute question ou collaboration.
