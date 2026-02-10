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

<img width="1441" height="1076" alt="Capture d&#39;écran 2026-02-03 200641" src="https://github.com/user-attachments/assets/5f65f3fd-d1f4-4d66-beac-ddadd794b47a" />
<img width="1436" height="1077" alt="Capture d&#39;écran 2026-02-03 200658" src="https://github.com/user-attachments/assets/c13346b3-52b7-47c0-b642-4c3df3932f9a" />
<img width="1435" height="1077" alt="Capture d&#39;écran 2026-02-03 200715" src="https://github.com/user-attachments/assets/f634a586-d332-4f7a-a528-12a231641352" />
<img width="1435" height="1073" alt="Capture d&#39;écran 2026-02-03 200737" src="https://github.com/user-attachments/assets/23496543-b15c-4d85-adaf-bdb0f1f63d28" />
<img width="1438" height="1074" alt="Capture d&#39;écran 2026-02-03 200751" src="https://github.com/user-attachments/assets/968332aa-aecd-4eb9-a6fa-caad6feefdb3" />
<img width="1439" height="1076" alt="Capture d&#39;écran 2026-02-03 200810" src="https://github.com/user-attachments/assets/febfcc01-6ff8-4557-a9aa-8b4c2209b1f9" />
<img width="1439" height="1076" alt="Capture d&#39;écran 2026-02-03 200821" src="https://github.com/user-attachments/assets/e463a498-0748-4ac1-820b-a59d4d2bc013" />

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
