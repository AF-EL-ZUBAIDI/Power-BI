# Analyse de l'Évolution de la Population

## Description
Ce projet Power BI montre l'évolution de la population dans plusieurs villes françaises entre 1793 et 2021. Il comprend un graphique linéaire illustrant les tendances démographiques dans les villes sélectionnées.

## Objectifs
- Visualiser les tendances démographiques historiques dans différentes villes françaises.
- Permettre un filtrage dynamique par ville et par période.
- Fournir des insights sur l'évolution de la population dans chaque ville.

## Données Utilisées
Les données proviennent de sources historiques et incluent les villes suivantes :
- Lyon
- Caen
- Marseille
- Pontault-Combault

Chaque table contient les colonnes suivantes :
- **Annee** (Année)
- **Population** (Nombre d'habitants)
- **ville** (Nom de la ville)

## Étapes de Préparation et d'Analyse

1. **Connexion aux Sources de Données**
   - Importation des données historiques de population pour chaque ville.

2. **Préparation des Tables Individuelles**
   - Ajout d'une colonne personnalisée `ville` pour chaque table afin d'identifier la ville correspondante.

3. **Combinaison des Tables**
   - Fusion des différentes tables en une table combinée `BDD` contenant les colonnes `Annee`, `Population`, et `ville`.

4. **Création des Visualisations**
   - **Graphique Linéaire :** 
     - Axe X : `Annee` (Année)
     - Axe Y : `Sum(Population)` (Somme de la population)
     - Série : `ville` (Ville)
   - **Segments de Données (Slicers) :**
     - `ville` (Ville)
     - `Annee` (Année)

## Résultat Final
![Graphique Linéaire](image.png)

### Auteur
[Votre Nom]

### Liens
- [Profil GitHub](https://github.com/nom-utilisateur)
