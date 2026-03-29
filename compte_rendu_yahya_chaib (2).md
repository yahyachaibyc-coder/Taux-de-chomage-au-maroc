# 📋 COMPTE RENDU

---

<div align="center">

## **CHAIB Yahya**

*Étudiant — ENCG Settat · Université Hassan 1er*

</div>

---

## 🪪 Informations Personnelles

| Champ               | Informations                        |
|---------------------|-------------------------------------|
| **Nom**             | CHAIB                               |
| **Prénom**          | Yahya                               |
| **Établissement**   | ENCG Settat — Université Hassan 1er |
| **Date du rapport** | 29 mars 2026                        |

---

## 📊 Objet du Compte Rendu

Ce compte rendu présente l'analyse et la visualisation des données relatives au **taux de chômage au Maroc**, réalisées dans le cadre des travaux pratiques de traitement et visualisation de données à l'ENCG Settat.

---

## 🛠️ Travaux Réalisés

### 1. Analyse des Données (Excel HCP)

- Exploitation du fichier de données trimestrielles du **Haut-Commissariat au Plan (HCP)**
- Période couverte : **2006T1 – 2025T3** (79 trimestres)
- Dimensions analysées :
  - Taux national (Ensemble)
  - Répartition par **milieu** (Urbain / Rural)
  - Répartition par **sexe** (Masculin / Féminin)
  - Répartition par **tranche d'âge** (15–24, 25–34, 35–44, 45 ans+)
  - Répartition par **niveau de diplôme** (Sans diplôme / Moyen / Supérieur)

### 2. Dashboard HTML Interactif

Création d'un dashboard HTML complet (Chart.js) avec :

- 6 onglets thématiques interactifs
- KPI cards dynamiques aux couleurs ENCG Settat (`#006633` / `#D4A017`)
- Graphiques linéaires, en barres, en donut et radar
- Tableau de données paginé et filtrable

### 3. Dashboard Excel Professionnel

Génération d'un classeur Excel multi-feuilles structuré :

- Feuille « Vue Générale » avec KPI et tableau comparatif
- 4 feuilles thématiques (Milieu, Sexe, Âge, Diplôme) avec graphiques intégrés
- Feuille « Données Complètes » avec formules `AVERAGE` et mise en forme conditionnelle
- Zéro erreur de formule (validé via LibreOffice)

---

## 📈 Principaux Résultats

| Indicateur                     | Valeur (2025T3) | Observation              |
|--------------------------------|-----------------|--------------------------|
| **Taux national**              | **13,1 %**      | ▼ −0,5 pt vs 2024T3      |
| **Taux urbain**                | 16,3 %          | Écart U–R : 9,4 pts      |
| **Taux rural**                 | 6,9 %           | Moins touché             |
| **Taux féminin**               | 21,6 %          | ▲ +11 pts vs hommes      |
| **Chômage jeunes (15–24 ans)** | **38,4 %**      | Priorité nationale       |
| **Diplômés du supérieur**      | **25,7 %**      | Paradoxe éducatif × 5,5  |
| **Non-diplômés**               | 4,7 %           | Taux le plus bas         |
| **Minimum historique**         | 7,8 %           | 2006T2                   |

---

## 💡 Observations et Recommandations

> **Paradoxe éducatif :** Les diplômés du supérieur présentent un taux de chômage **5,5 fois plus élevé** que les non-diplômés (25,7 % vs 4,7 %), révélant un décalage structurel persistant entre l'offre de formation et les besoins réels du marché de l'emploi marocain.

**Points d'attention identifiés :**

- La fracture territoriale **Urbain/Rural** (9,4 pts d'écart) reste significative et persistante sur toute la période.
- L'inégalité de genre demeure marquée avec un écart **Femme/Homme de +11 pts**.
- Le chômage des **jeunes de 15 à 24 ans** (38,4 %) constitue le défi socio-économique le plus urgent.
- Une tendance légèrement positive est visible sur le **taux national** depuis 2024T1 (pic à 13,7 %).

---

## 🔧 Outils Utilisés

| Outil                     | Usage                                         |
|---------------------------|-----------------------------------------------|
| **Python / pandas**       | Lecture et traitement des données Excel       |
| **openpyxl**              | Génération du dashboard Excel formaté         |
| **Chart.js 4.x**          | Graphiques interactifs dans le dashboard HTML |
| **HTML / CSS / JS**       | Interface du dashboard web                    |
| **Claude AI (Anthropic)** | Assistance à l'analyse et génération de code  |

---

## 📁 Livrables

- `dashboard_chomage_maroc.html` — Dashboard interactif (6 onglets, responsive)
- `dashboard_chomage_maroc.xlsx` — Classeur Excel professionnel (6 feuilles + graphiques)
- `compte_rendu_yahya_chaib.md` — Présent compte rendu

---

<div align="center">

---

*Compte rendu rédigé par **CHAIB Yahya***  
*ENCG Settat — Université Hassan 1er · Mars 2026*

</div>
