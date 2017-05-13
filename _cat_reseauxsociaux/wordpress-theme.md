---
layout: article
title: Mettre son blog Wordpress aux couleurs de la France Insoumise
contentdescription:
icon: wordpress-theme.svg
sortinglabel: wordpress-l2
---

## Prérequis

Si vous souhaitez utiliser le thème sur votre propre serveur, voici les prérequis :
- WordPress >= 4.7
- PHP >= 5.6.4
Plus d'informations ici : https://github.com/roots/sage. 


## Installer le thème

Afin d’installer le thème “FI 2017”  dans une installation wordpress que vous avez déjà il est nécessaire d’utiliser l’extension github-updater. Elle vous permettra aussi de mettre à jour le thème à l'avenir.
Installation du plugin (tuto vidéo anglais) :
1. Téléchargez la dernière version au format ".zip" <https://github.com/afragen/github-updater/releases/>
2. Décompressez l’archive, renommez le dossier “github-updater” puis zippez-le à nouveau.
3. Rendez-vous dans  “Extensions > Ajouter”, puis “Mettre une extension en ligne”. Sélectionnez l'archive .zip, puis cliquez sur installer.
4. Activez l’extension.

Vous pouvez désormais installer le thème :
1. Dans la liste de vos extensions cliquez sur “réglages” de l’extension github-updater. Allez dans “installer le thème”.
2. Dans “Thème URI” copiez cette adresse : <https://github.com/insoumis-local/wordpress-template-legislatives>. Ne touchez pas au reste et cliquez sur “Installer le thème”.
3. Dans “Thèmes” vérifier que “FI 2017” est activé. Si ce n’est pas le cas, activez-le. 

*En cas de problème, consultez la documentation (EN) du plugin : <https://github.com/afragen/github-updater/wiki> avant de nous contacter.*

## Mises à jour

![Mise à jour du thème](/assets/images/screenshots/majtheme.png)

Se rendre dans "Apparence > Thèmes" et cliquer sur "Mettre à jour automatiquement".  Wordpress est censé vous notifier lors de la disponibilité d'une mise à jour. Si ce n'est pas le cas, vous pouvez vous rendre dans "Réglages > GitHub Updater" et cliquer sur "Actualiser le cache", puis revenir dans "Apparence > Thèmes". La notification devrait apparaître. En cas de doute, vérifiez que le numéro de version corresponde à celui indiqué ici : <https://github.com/insoumis-local/wordpress-template-legislatives>/blob/master/style.css. 
Si vous utilisez notre service d'hébergement générique, le thème sera mis à jour automatiquement par nos soins.


## Créer du contenu

<https://github.com/insoumis-local/wordpress-template-legislatives/blob/master/README.md> 

**Pour modifier l'en-tete de la page d’accueil** : Dans "Apparence > Personnaliser > FI 2017 HOME" il est possible de définir les infos de base pour afficher le cartouche d'accueil. Ce cartouche ne s'affiche que sur la page d'accueil. Vous pourrez alors choisir une image, indiquer le nom des candidats, la circonscription ainsi que les villes de la circonscription. Pour désactiver cet en-tete il suffit de décocher la case "activer l'en-tete". 

Le template de contenu "Blue card only" correspond à la home de <https://lafranceinsoumise.fr>

Le template de contenu "Home" permet d'utiliser l'image mise en avant comme fond et le texte comme contenu de la barre positionnée sur l'image. Il permet donc de faire une page d'accueil différente du modèle fourni par le cartouche.

Il y a trois zones pouvant accueillir des widgets :

- **Sidebar** : la barre latérale droite sur les pages qui en disposent
- **Pre Footer** : la zone bleue en base de page avant le footer
- **Pied de page** : le footer tout en bas de page

Il y a quatre zones pouvant accueillir des menus :

- **Navigation Primaire** : barre blanche à droite du logo sur toutes les pages
- **Secondary Navigation** : barre orange sous la Navigation Primaire
- **Blue card only Left Nav** : espace à gauche de la zone bleue sur le template "Blue card only"
- **Blue card only Right Nav** : espace à droite de la zone bleue sur le template "Blue card only"

