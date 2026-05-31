# Création d'une base de données immobilière — SQL

> Concevoir et peupler une base SQL normalisée (3NF) à partir de 500 000 transactions foncières DVF — schéma relationnel documenté.

**Stack** · SQL · PostgreSQL · DBeaver · Excel

---

## Contexte

Un réseau d'agences immobilières souhaitait structurer les données de valeurs foncières (DVF) publiées par le gouvernement français pour en faire un outil d'analyse de marché. Ce projet couvre la modélisation, la normalisation et le peuplement d'une base de données relationnelle complète.

## Méthodologie

1. **Analyse du dictionnaire DVF** — compréhension des entités, cardinalités, types de données
2. **Modélisation ERD** — conception du schéma entité-relation
3. **Normalisation 3NF** — élimination des redondances, clés primaires et étrangères
4. **Implémentation SQL** — création des tables, contraintes d'intégrité
5. **Peuplement** — chargement des 500 000 transactions depuis les fichiers sources
6. **Requêtes d'analyse** — prix au m², évolution par commune, transaction par type de bien

## Résultats clés

- Base normalisée intégrant communes, biens, mutations et acteurs
- 500 000 transactions DVF importées et requêtables
- Requêtes d'analyse couvrant les KPIs marché immobilier

## Contenu du repo

| Fichier | Description |
|---------|-------------|
| `dictionnaire_de_donnees.xlsx` | Dictionnaire de données complet avec types, contraintes et relations |
| `presentation.pptx` | Modèle ERD, schéma SQL et exemples de requêtes |

---

*Formation Data Analyst — OpenClassrooms × ENSAE · Projet 4*
