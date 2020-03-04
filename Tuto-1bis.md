
-----------------------------
Fichier: Tuto-1bis
Par: Pascal Richet
Date: 4/03/2020
Thématique Gestion de Github
-----------------------------

* En complément au premier Tuto-1

# Les fichiers qui accompagnent tous dépôt

Vous venez de créer votre nouveau dépôt sur Github ... Ou bien vous faites une mise à jour d'un dépôt existant.

Dans les deux cas, il y a des fichiers qui doivent absolument être présent. L'objectif de tout dépôt est qu'il doit être compréhensible par la communauté Github ainsi qu'a toute personne qui souhaite intéragir avec votre projet. 

## .gitignore

1. Pourquoi ce nom ? 

Il apparaît souvent qu’un type de fichiers présent dans la copie de travail ne
doit pas être ajouté automatiquement ou même ne doit pas apparaître comme
fichier potentiel pour le suivi de version. Ce sont par exemple des fichiers générés
automatiquement tels que les fichiers de journaux ou de sauvegardes produits
par l’outil que vous utilisez. Dans un tel cas, on peut énumérer les patrons
de noms de fichiers à ignorer dans un fichier .gitignore. Voici ci-dessous un
exemple de fichier .gitignore :

	.DS_Store
	*.txt 

Cas typique pour mac.

GitHub maintient une liste assez complète d’exemples de fichiers .gitignore
correspondant à de nombreux types de projets et langages. Voir 
[Github fichier .gitignore](https://github.com/github/gitignore) pour obtenir un point de départ pour votre projet.

Dans ce dépôt, vous avez une collection de template assez impressionnante en fonction du stack spécifique à votre projet.

Vous avez du 'kotlin' dans votre projet du 'ruby' ou que sais je encore, alors piocher dans l'un de ses 'template' et au besoin adapter le.

Fichier à créer dans votre projet

	$ touch .gitignore

Ou bien copier/coller le template fourni par le site. (voir link précèdent).

## ReadMe (Englsh/Français version)

A well written ReadMe is one of the most important parts of a good repository ...

Documenter votre dépôt avec l'aide du fichier ReadMe, l'étape la plus importante ...

## Anatomy of a ReadMe file

## Anatomie d'un fichier ReadMe

Keep in mind, we are writing for other humans!!

Toujours se rappeler, l'on écrit pour des humains !!


We'll start with a title and a description ... instructions, installation, common usage, know bugs, ...

Comment commencer ? 

Un titre, une petite description, des instructions pour utiliser le projet et au besoin pour l'installer.

The longer depends of the complexity of your project.

Pas besoin dans faire des tonnes, il faut aller à l'essentiel !!

Any information that is essential for the user.

Toujours dans l'idée dans faire, une sorte de mode d'emploi, destiner à un usagé.

You decide what is essential and what is not!!

C'est vous, l'équipe, qui décidez ce qui est important ou pas !

Just folow this step ...

Voiçi les étapes à suivre ...

1. What steps need to be taken?
2. What should the user already have installed or configured?
3. What might they have a hard time understanding right away?

1. Quels sont le étapes ?
2. Que doit avoir installer l'utilisateur pour faire fonctionner le projet ?
3. Les difficultés potentiels 

The right question is ...

Les bonnes questions sont ...

* What the end user expected to know?

* Qu'est ce que l'utilisateur final doit savoir ?

* Think about it from the perspective of someone who's never seen this before.

* L'idée générale au fond, se mettre à la place d'une personne disons débutante. 

You can allow others to contribute to your project and you must mention it inside a ReadMe file.

Dans ce fichier, vous pouvez renseigner notamment, si il est possible de contribuer au projet.

In this case is, super important, to include a license or you can link out to it from your ReadMe.

Dans ce dernier cas, il est super important d'inclure une licence adapter à votre projet.

Techniquement, le fichier ReadMe est souvent écrit en markdown. Cependant tous les formats semble accepter.

**L'idée générale est que le fichier doit être le plus clair possible !!**

[Github Flavored Markdown](https://help.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github)

[Writing on Github](https://help.github.com/en/github/writing-on-github)

## Le choix de la licence

**L'idée générale est de protéger votre travail, même si celui-ci est open source.**

plus d'information ici. ( En anglais ...)

[Github help](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository)

[Github blog](https://github.blog/2013-07-15-choosing-an-open-source-license/)

ou là ...

[License](choosealicense.com)

