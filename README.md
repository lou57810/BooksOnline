# BooksOnline
P2_01_Book.py	Premier script demandé: Affiche les données d'un livre au hasard.

P2_02_CategoryBook.py Deuxieme script: Affiche les données livres d'une catégorie au hasard.

P2_03_AllBooks.py : Affiche les données livres de chaques catégories,
et enregistrées séparément dans des fichiers .csv avec le nom de la catégorie dans un dossier listeParCat
et les images dans un dossier img, dossiers qui seront créés lors de l'exécution du script.

Pour réussir à developper et executer ces applications en langage python,
il est nécessaire de créer un environnement vierge:
1. Création d'un dossier acceuillant les scripts.
2. Dans ce dossier, on crée cet environnement à l'aide de la commande:
	$ python -m venv env
3. Selon le système d'exploitation, on utilisera la commande suivante:
	Linux:	 $ source env/bin/activate		(deactivate pour desactiver)
	Windows cmd.exe: $ env\Scripts\activate.bat	(Attention à l'antislash) (deactivate pour desactiver)
4. A ce stade la commande $ pip freeze restera sans réponse, car aucun module
	ne sera encore installé.
5. Le fichier requirements.txt permet de récupèrer l'installation de tous les
 modules requis pour les applications présentes dans l'environnement, avec la 
 commande: $ pip install -r requirements.txt

Les scripts peuvent alors s'executer normalement.
