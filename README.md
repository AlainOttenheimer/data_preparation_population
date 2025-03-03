# data_prep_population
jupyter notebook pour mettre les données du fichier POP_1B - population par sexe et par âge - dans une forme adéquate pour réaliser des pyramides des âges. 

le fichier POP_1B_2021.xlsx est téléchargeable sur la page de l'INSEE [Population en 2021 Recensement de la population - Base des tableaux détaillés] (https://www.insee.fr/fr/statistiques/8202264?sommaire=8202287)

Le traitement consiste à : 
- Créer une colonne nbr d'hommes dans la commune 
- Créer une colonne nbr de femmes dans la commune 
- d'ajouter pour chaque commune les colonnes : code_dept, nom_departement, code_reg, nom_region 
- de selectionner toutes les communes d'une région
- de sélectionner les 25 communes les plus peuplées de la région 
- transposer les colonnes par âge en trois colonnes : Age, Nb_H et NbF
- créer un fichier csv charger dans l'application observable [population-de-villes-doccitanie-en-2021] (https://observablehq.com/@tdvz/population-de-villes-doccitanie-en-2021)


<img height="500" src="https://github.com/AlainOttenheimer/data_prep_population/pyramide_tls.PNG" style="border:0;box-shadow:none"><br>


- Placer le Le fichier .ipynb dans répertoire 
- Dans ce repertoire créer un dossier data et y placer les données data de ce repository.
- Toujours dans ce repertoire créer un dossier result.  
