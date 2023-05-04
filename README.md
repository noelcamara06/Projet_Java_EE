# Projet_Java_EE

##Préalable
Chaque Etudiant aura à faire, un projet fourni par l’enseignant, parmi ceux cités ci-dessous.
L’étudiant doit :
Analyser, concevoir et réaliser le projet seul,
Utiliser les langages Java, Javascript, HTML5, CSS3 avec la plateforme Eclipse, Utiliser MySQL,
 Fournir son travail dans un dossier parent portant son nom ainsi :
« INGETIS_Web_2022_06_Paris_Nom_Prenom » : remplacer Paris par Evry si nécessaire.
Exemple : Je me nomme DUVAL Paul et je suis en 5ème Année Paris :
Mon dossier à fournir se nommera INGETIS_Web_2021_05_Paris_DUVAL_Paul»
Ce dossier contiendra côte à côte : le projet Web + la documentation Word ou PDF
Fournir la documentation Word ou PDF : Elle doit contenir des informations bien précises :
Entête :
- Nom, prénom, Classe, Date
- Pied de page :
- Votre Courriel
- 1ère Page :
- Le N° du projet et sa description : copiez /collez la description du projet de ce PDF,
- Les autres pages :
- Une explication détaillée de votre solution : choix des pages : nombre et contenu,
Des tables SQL : nombre, contenu, relations, et toute info utile.
- Un schéma de navigation entre les pages,
- Un schéma de la base de données : schéma des tables SQL et leurs relations (MSD ou MLD),
- Mode de test : expliquer, si nécessaire, ce qu’il faut créer, installer pour tester votre projet ;
- Conclusion : ce qui est fini ou pas fini. Difficultés rencontrée.
Fournir le projet :
- Le dossier qui contient le projet Eclipse (ne me donnez pas le Workspace avec pleins de projets dedans),
- Un dossier ressources (même s’ils sont déjà dans le projet Eclipse) :
- Le script SQL complet qui permet de créer la BD et la remplir par des données de tests.
- Le fichier .css pour la mise en page,
- Le ou les fichiers javascript utilisés,
- Autres ressources : images, logos, …
Comment sera noté le projet : Le Top est :
 Convention de nommage :
Nommer avec clarté : les pages, les variables, les fonctions, les fichiers : pensez à un développeur qui
Prendra la suite de vos développements,
- Réduire le code serveur (du java) dans les pages au minimum : privilégier l’appel aux méthodes dans des classes Java,
- Ne pas appeler la BD dans les pages, mais appeler des méthodes java dans des classes (revoir classe paramètres utilisée en cours),
- Isoler le code navigateur (Javascript) dans un/des fichier (s) externe, au lieu de le coder dans la page,
Ne pas appeler une page dans une page mais passer par un contrôleur (fichier .jsp),
- Appliquer à toutes les pages, la même mise en page via une feuille de style (.css),
- Si vous finissez le travail en fin de journée : vous serez noté sur 20,
- Si vous ne finissez pas en fin de journée : une note sur 13 sera attribuée, pour le travail rendu en fin de journée (projet web + doc) et une note sur 7 pour le reste à finir avec date butoir.


##Projet N°8

On souhaite gérer l’organisation des voyages en avion d’une compagnie aérienne.
Cette gestion inclura :
- La gestion des destinations (liste, fiche, ajouter, modifier, supprimer, vols prévus),
- La gestion des vols d’une destination (liste, fiche, ajouter, modifier, supprimer, passagers, avion),
- La gestion des passagers d’un vol (liste, fiche, ajouter, modifier, supprimer)
- La gestion des sièges d’un avion (liste).

Version 2 : en option
- Ajouter une photo à une destination, ajouter une photo à l’avion.
- Générer un PDF de la liste des passagers d’un vol.
