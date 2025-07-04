# 📊 Styleesh - Dashboard Décisionnel

Bienvenue dans ce repository dédié au workshop **MBA1 Big Data - Projet Styleesh**.  
Ce projet a pour objectif de poser les fondations d'une stratégie **data-driven** pour l'entreprise **Styleesh**, spécialiste de la vente de vêtements en ligne.

---

## 🧩 Objectif du projet

Styleesh collecte de nombreuses données (ventes, clients, trafic web…) sans les exploiter efficacement.  
L’objectif de ce projet est de construire un **premier tableau de bord décisionnel** permettant de :

- Suivre les ventes par **catégorie**, **pays** et **canal d’acquisition**
- Comprendre les **comportements clients**
- Identifier les **produits à fort potentiel** ou en **baisse de régime**

---

## 🛠️ Contenu du repository

```bash
├── dashboard/
│   └── dashboard_styleesh.pbix
├── data/
│   ├── open_data/
│   │   └── reve-conso-evo-dep-pa.xlsx
│   ├── provided_data/
│   │   ├── customers.csv
│   │   ├── products.csv
│   │   ├── sales.csv
│   │   └── website_traffic.csv
├── schema/
│   ├── Analytical database schema (star model).jpg
│   └── Analytical database schema (star model).drawio
├── statement/
│   └── MBA1 Big Data workshop statement.docx
├── Dossier final - Styleesh.docx
├── Dossier final - Styleesh.pdf
└── README.md
```

---

## 📝 Méthodologie

### 1. Audit des données
- Vérification de la **qualité**, **cohérence** et **complétude** des données
- Correction de typages et valeurs incohérentes (ex. remises > 1)

### 2. Nettoyage & préparation
- Conversion de formats (dates, remises)
- Uniformisation des formats
- Suggestions d'enrichissement (sources d'acquisition, géolocalisation)

### 3. Modélisation analytique
- Mise en place d’un **modèle en étoile**
- Fait central : Ventes  
- Dimensions : Produits, Clients, Canaux, Temps

### 4. Définition des KPIs
- Chiffre d'affaires, taux de rebond, panier moyen, produits en stock dormant, etc.

### 5. Réalisation du tableau de bord Power BI
- 5 vues : Vue globale, Vue client, Vue marketing, Vue alertes et Conjoncture

### 6. Enrichissement avec données externes
- Utilisation de sources comme **INSEE**, **Google Trends**, **météo**, etc.

---

## Résultats

- Mise en place d’un premier tableau de bord interactif Power BI
- Proposition d’une architecture analytique simple
- Liste de recommandations concrètes pour initier une **culture data**

---

## Recommandations

- Déploiement d’outils comme **Power BI** ou **Looker Studio**
- Mise en place d’un **datawarehouse simplifié**
- Sensibilisation des équipes à l’usage des KPIs
- Suivi automatisé par **reporting mensuel**

---

## Ressource externe utilisée

- [INSEE - Évolution de la dépense et du pouvoir d’achat des ménages](https://www.insee.fr/fr/statistiques/2385829)
---

## D'autres qui pourraient être utilisées

- [INSEE - Statistiques et études](https://www.insee.fr/fr/statistiques)
- [Google Trends](https://trends.google.com/)
- [Open Meteo Data](https://open-meteo.com/)
- [Calendrier scolaire & jours fériés](https://data.gouv.fr)

---

## Auteur

**Tristan Fioroni**  
Étudiant MBA1 Big Data | Projet réalisé dans le cadre d’un workshop académique  
👨‍🎓 [LinkedIn](https://www.linkedin.com/in/tristanfioroni/)
👨‍💼 [GitHub](https://github.com/Titi7750)
👨‍💻 [Agence](https://datamaniacs.fr/)

---

## 📝 Licence

Ce projet est à but pédagogique. Toute réutilisation des données ou du code est libre dans un cadre académique ou personnel.
