# Utilisation  
## Création des fichier SQL à partir des SHAP files 
- copier le ficher shp_sql dans le dossier contenant vos shape files 
- rendre le fichier shp_sql executable avec la commande **chmod u+x shp_sql**
- executez le fichier avec la commande **./shp_sql srid** ou srid represente votre srid exple 3405 pour le vietname
- apres execution verifiez votre dossier et vous allez trouver les differents fichier sql a importer dans votre base de données

## Importation des fichier SQL dans la base de données 
- copier le ficher sql_db dans le dossier contenant vos sql  files 
- rendre le fichier sql_db  executable avec la commande **chmod u+x sql_db**
- lancer la commande **./sql_db database user**  ou __database__ est le nom de votre base de données et __user__ le nom de l'utilisateur  
__NB: Si votre utilisateur postgres a un mot de passe, ce mot de passe sera demander a chaque importation__ 
