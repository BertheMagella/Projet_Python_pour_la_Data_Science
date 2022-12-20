# PROJET PYTHON POUR LA DATA SCIENCE 2022

# THEME : ANALYSE DES AVIS DES STAGIAIRES ET EMPLOYES DE SOCIETE GENERALE TRANSMIS VIA LA PLATEFORME INDEED.COM ENTRE 2012 ET 2022  

## Auteurs:
* TALEB AHMED Raja
* MAGAJIE WAMSA Berthe Magella
* RENE Léo

## A propos du projet
Ce projet s'inscrit dans le cadre du cours de Python pour la Data Science dispensé en deuxième année du cycle ingénieur de l'ENSAE Paris; l'objectif étant de mettre en application tous les fondamentaux acquis jusqu'ici. 
Nous avons opté pour une analyse des avis des stagiaires et employés de la Société Générale(SG) transmis via la plateforme Indeed.com dans l'optique de permettre aux étudiants, particulièrement ceux de l'ENSAE, de se faire une idée sur l'environnement de travail au sein de la SG au travers des retours d'expériences de ceux qui ont intégré la structure. Aussi, la SG fait partie des recruteurs potentiels des profils ENSAE en nombre relativement important. 
Ce projet pourrait également être utile à la SG, permettant d'améliorer le quotidien des employés et stagiaires.  

## Organisation du code
Le projet est conduit sur deux notebooks à savoir :
* scrapping.ipynb : ce notebook a été créé pour la récupération des données sur le site Indeed.com et le regroupement des fichiers obtenus  
* Analyse&NLP.ipynb : il s'agit du notebook final qui contient le traitement des données, l'analyse et la modélisation. 

## Les données
Les données utilisées dans ce projet ont été scrappées sur la plateforme Indeed et sont contenues dans le fichier *'Database.cvs'*. Ce fichier a été construit à partir des fichiers *.txt*, créés pour contenir les données récupérées par scrapping pour chaque pays : *SG-FR.txt* pour la France, *SG-US.txt* pour les US et *SG-IN.txt* pour l'Inde.