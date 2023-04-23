# product-and-package-database
README pour le code d'analyse de la table product

Ce code permet de charger et d'analyser la table product à partir du fichier "product2.csv" stocké dans le répertoire "/kaggle/input/database2-tp/".

Le code utilise les librairies Python suivantes :
- sklearn
- numpy
- scipy
- pandas
- matplotlib.pyplot
- seaborn

La première partie de l'analyse consiste à effectuer une auscultation des données. Cette étape a pour but de donner un aperçu global sur la nature et la qualité des données. 

Pour cela, nous avons tout d'abord affiché les dimensions de la table product, ainsi que la liste des attributs. Ensuite, nous avons obtenu des informations sur les types de données, le nombre de valeurs manquantes et le nombre de valeurs uniques pour chaque attribut. 

Nous avons également établi un tableau résumant les attributs ayant des valeurs manquantes, triés selon le nombre de valeurs manquantes et le pourcentage de valeurs manquantes.

Enfin, nous avons vérifié que les dates de commercialisation des produits étaient cohérentes, en recherchant les cas où la date de début de commercialisation est postérieure à la date de fin de commercialisation.

Au total, la table product comporte 20 attributs et 93238 observations. Parmi ces attributs, 3 sont des dates : STARTMARKETINGDATE, ENDMARKETINGDATE et LISTING_RECORD_CERTIFIED_THROUGH. Pour le reste des attributs, nous avons affiché des informations sur les types de données et la présence de valeurs manquantes.
