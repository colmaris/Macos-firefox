Voici le userChrome.css que j'utilise avec Firefox pour qu'il soit raccord avec mon thème I3wm. J'ai aussi modifié sa structure car je ne supporte pas les onlgets au dessus de la barre d'aresse.

![image](https://draconis.me/images/2019/10/firefoxcss.gif)

N'étant pas développeur j'ai associé des morceaux de codes que j'ai trouvé :

* sur différentes sources internet pour les couleurs. 

* sur le groupe reddit [r/firefoxcss](https://www.reddit.com/r/FirefoxCSS/comments/bg4oqd/responsive_one_liner/) pour la partie de la barre cachée.

### Pour utiliser ce fichier sous windows :

1. [Télécharger](https://framagit.org/draconis/firefoxcss/-/archive/master/firefoxcss-master.zip) le fichier userChrome.css
2. Se rendre dans le dossier *C:\Users\"nom utilisateur"\AppData\Roaming\Mozilla\Firefox\Profiles\"profile_mozilla".default* 
3. Créer le dossier *chrome* s'il n'existe pas
4. Copier le fichier *userChrome.css*
5. Ouvrir Firefox et taper about:config dans la barre d'adresse
6. Chercher la ligne *toolkit.legacyUserProfileCustomizations.stylesheets* et changer sa valeur à *true*
7. Redémarrer firefox et profiter

### Pour utiliser ce fichier sous linux :

1. [Télécharger](https://framagit.org/draconis/firefoxcss/-/archive/master/firefoxcss-master.zip) le fichier userChrome.css
2. Se rendre dans le dossier *~/.mozilla/firefox/"profile_mozilla".default/* 
3. Créer le dossier *chrome* s'il n'existe pas
4. Copier le fichier *userChrome.css*
5. Ouvrir Firefox et taper about:config dans la barre d'adresse
6. Chercher la ligne *toolkit.legacyUserProfileCustomizations.stylesheets* et changer sa valeur à *true*
7. Redémarrer firefox et profiter