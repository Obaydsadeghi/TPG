# Analyse de l'Accessibilité et de l'Efficacité des Réseaux de Transport Public dans le Canton de Genève

## Description du Projet
Ce projet ArcGIS Pro examine l'accessibilité et l'efficacité des réseaux de transport public dans le canton de Genève. Il utilise divers outils de géotraitement pour analyser les données relatives à la population, la densité de population, et la proximité des arrêts de transport public.

## Prérequis
Pour utiliser ce projet, vous devez avoir :
- ArcGIS Pro 3.x installé sur une machine Windows.
- Une connexion active à Internet pour accéder aux données du serveur PostgreSQL si nécessaire.

## Installation
1. **Téléchargement du Projet** :
   - Clonez ou téléchargez ce repository GitHub sur votre machine locale.
   - Ouvrez le fichier de projet `.aprx` avec ArcGIS Pro.

2. **Configuration de la Connexion** :
   - Si vous avez des identifiants pour la connexion à la base de données de l'Université de Genève, configurez la connexion en allant à `Catalog -> Toolboxes -> TPG.atbx -> Connection`.
   - Si vous n'avez pas d'identifiants, utilisez la connexion préconfigurée disponible à `Catalog -> Folders -> TPG -> Conn -> postgis_connection.sde`.

3. **Utilisation des Outils de Géotraitement** :
   - **Outil de Téléchargement et de Conversion** : Exportez les couches nécessaires du serveur à votre machine locale via `Catalog -> Toolboxes -> TPG.atbx -> Convertir`.
   - **Outil de Création de Buffer** : Crée des zones tampons autour des arrêts de transport public pour analyser l'accessibilité.
   - **Outil de Sélection par Localisation** (SelectByLocation) : Identifie les adresses non desservies par les transports publics.
   - **Outil de Calcul de la Population** : Calcule la population totale et non desservie par commune.

4. **Exécution des Scripts Python** :
   - Ouvrez et exécutez le Notebook Python à `Catalog -> Folders -> TPG -> New Notebook.ipynb` pour traiter les données et visualiser les résultats.

## Contribution
Les contributions à ce projet sont bienvenues. Veuillez suivre les pratiques standard pour proposer des améliorations ou des corrections.

## Licence
Ce projet est distribué sous une licence qui permet l'utilisation, la distribution, et la modification pour des fins non commerciales.

## Contact
Pour toute question ou demande, veuillez contacter [obayd.sadeghi@gmail.com].

Nous espérons que ce projet vous aidera à comprendre les défis et opportunités liés à l'amélioration de l'accessibilité aux transports publics dans le canton de Genève.
