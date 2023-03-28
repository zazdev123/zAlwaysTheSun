# Comment installer PhpMyAdmin sur Pterodactyl

Une installation de Pterodactyl (au dessus ou égale à 1.0) est requise, une base de données reliée au panneau et le package sudo, wget et unzip.

Tout d'abord, nous allons commencer par se rendre dans le directory, donc par défaut :

```sh
cd /var/www/pterodactyl/public
```

Ensuite, nous allons télécharger le fichier .zip de PhpMyAdmin contenant toutes les langues et l'extraire :

```sh
wget https://files.phpmyadmin.net/phpMyAdmin/5.2.1/phpMyAdmin-5.2.1-all-languages.zip && unzip phpMyAdmin-5.2.1-all-languages.zip
```

Ensuite, nous allons déplacer le dossier dans le directory /phpmyadmin et lui accorder des permissions pour correctement fonctionner :

```sh
mv phpMyAdmin-5.2.1-all-languages phpmyadmin && chmod 777 phpmyadmin
```

Vous pouvez désormais accéder à phpmyadmin en accédant à l'URL http(s)://\<nom-de-domaine>/phpmyadmin

**Tutoriel terminé ! En voir plus, c'est ci dessous ! ⬇️**
