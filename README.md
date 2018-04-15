# Utilisation 
## Création des fichier SQL à partir des SHAP files 
- copier le ficher shp_sql dans le dossier contenant vos shape files 
- rendre le fichier shp_sql executable avec la commande *chmod u+x shp_sql*
- executez le fichier avec la commande **./shp_sql srid  database** ou srid represente votre srid exple 3405 pour le vietname et database votre base de donneés créee dans votre SGBD sinon vous aurez des fichier sql sans SRID et Base de données
- apres execution verifiez votre dossier et vous allez trouver les differents fichier sql a importer dans votre base de données

## Importation des fichier SQL dans la base de données 
- copier le ficher sql_db dans le dossier contenant vos sql  files 
- lancer la commande **./sql_db** database  ou database est le nom de votre base de données   
