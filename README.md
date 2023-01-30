# Implémentation d'une solution ETL pour l'intégration de données et gestion des BigData sous Talend




![GitHub](https://img.shields.io/github/license/kebiri-isam-dine/Implementation-d-une-solution-ETL-et-gestion-des-BigData-sous-Talend?color=g&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/kebiri-isam-dine/Implementation-d-une-solution-ETL-et-gestion-des-BigData-sous-Talend?color=red&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/kebiri-isam-dine/Implementation-d-une-solution-ETL-et-gestion-des-BigData-sous-Talend?color=yellow&style=for-the-badge)

![GitHub dev_language](https://img.shields.io/badge/Talend-green?style=flat&logo=talend&logoColor=white)
![GitHub dev_language](https://img.shields.io/badge/PostgreSQL-blue?style=flat&logo=postgresql&logoColor=white)
![GitHub dev_language](https://img.shields.io/badge/Oracle-red?style=flat&logo=oracle&logoColor=white)


![GitHub Org's stars](https://img.shields.io/github/stars/kebiri-isam-dine?style=social)
![GitHub followers](https://img.shields.io/github/followers/kebiri-isam-dine?style=social)




## About The Project

『 EN COUR DE REALISATION 』   
Ce projet consiste à implémenter une solution ETL (Extract-transform-load) sous **Talend Open Studio** pour une intégration de différentes sources de données et notamment avec des scripts en **java**, les taches à réaliser sont :

- Implémenter des jobs
- Réaliser des mapping avec les flux de données
- Orchestrer plusieurs jobs et création des routines pour transformation de données
- Intégration de deux bases de données : **PostgreSQL** et **Oracle**
- Définition des schémas de métadonnées
- Automatisation avec des scripts exécutable
- Gestion des grosses sources de données (**Big Data**)

#### context

- Migration de données à un nouveau système
- Stockage de données dans des entrepôts de données
- Consolidation de données (fusion d'entreprises)
- Synchronisation de données
- Lectures de différents DBs ou fichiers (csv, txt, excel, xml ou plat)
- Intégration décisionnelle et opérationnelle

#### Keywords

Talend  - java - jobs - PostgreSQL - Oracle

## Dataset

Le dossier des fichiers csv, excel et txt de données se trouve [ici](/Data_csv/Fichiers/)

Processus | Inputs | Outputs | Description                                      |
|-----------------|-----------------|----------------------------------|---------------------------------------------|
| Id1 | [Fichier_Individus.csv](/Inputs/Fichier_Individus.csv)| [Individus.xml](/Outputs/Individus.xml)| Lire un csv et le transformer en xml|
| Id 2 | [Fichier_Individus.csv](/Inputs/Fichier_Individus.csv)| [Individus_MAJ.csv](/Outputs/Individus_MAJ.csv)| Mettre la cologne nom en MAJ|
| Id3 | [Fichier_Individus.csv](/Inputs/Fichier_Individus.csv) & [Activite_Individus.txt](/Inputs/Activite_Individus.txt)| [Id3IndividuOutput.csv](/Outputs/Id3IndividuOutput.csv) & [Id3IndividuOutput.xml](Outputs/Id3IndividuOutput.xml)| csv + txt to csv & xml. <br>  Ajout de la colone type_sport présente dans txt au csv|
| Id4 | [Fichier_Individus.csv](/Inputs/Fichier_Individus.csv)| [Individus_MAJ.csv](/Outputs/Individus_MAJ.csv)| Mettre la cologne nom en MAJ|
## Taches réalisées

- Créations et configuration des **jobs** composée de plusieurs composants reliés par des connexions
- Exécution des jobs et débogage du code
- Load csv & transform to xml
- Transformer un fichier csv : mettre les noms en MAJ
- ...

## Visualisation des processus

Exemple du processus [csv_to_xml.java](C:\Users\etudiant\OneDrive\My_Documents\Projects\Code\DB\Implementation-d-une-solution-ETL-et-gestion-des-BigData-sous-Talend\poms\jobs\process\Utilisation_fichiers\utilisation_fichier1_0.1\src\main\java\main1\utilisation_fichier1_0_1\Utilisation_fichier1.java) :
<img src="/Captures/Processus_Id_2.png">



## License

[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## Contact

📫 How to reach me: kebiri.isam.dine@gmail.com

🌐 My Portfolio: <https://kebiri-isam-dine.github.io/>

🔗 Project Link: <https://github.com/kebiri-isam-dine/Implementation-d-une-solution-ETL-et-gestion-des-BigData-sous-Talend>