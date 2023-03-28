# Installer Fail2Ban sur Ubuntu ou Debian

Pour commencer, veuillez d'abord exécuter les commandes suivantes :

$ sudo apt install fail2ban

Toutes ls commandes ci-dessus sont adaptées pour Ubuntu 20.04, 16.04, Debian 8, 9 et 10.

Une fois ceci fait, vous pourrez fouiller dans le fichier de configuration ci-dessous :

$ sudo cp /etc/fail2ban/jail.conf /etc/fail2ban/jail.local $ sudo vim /etc/fail2ban/jail.local

Et voilà, vous avez juste à entrer ce qui vous convient ou non, vous redémarrez Fail2Ban avec la commande suivante :

$ sudo systemctl restart fail2ban

**Tutoriel terminé ! En voir plus, c'est ci dessous ! ⬇️**
