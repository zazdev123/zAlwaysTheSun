# Installer Pterodactyl

Afin d'installer Pterodactyl, vous aurez besoin de: \
\- Un serveur VPS/VDS/Serveur Dédié avec accès ROOT user\
ou\
\- Un ordinateur avec Ubuntu (18.04, 20.04, 22.04)/Debian (10, 11) installé\
\
Tout d'abord, vous aurez besoin d'effectuer la commande suivante afin de mettre à jour le serveur/PC et d'installer les packets nécessaires :

```sh
apt update && apt full-upgrade -y && apt install bash sudo curl wget -y
```

Une fois ceci fait, je vous conseille d'utiliser le script de vilhelmprytz, qui vous permettra d'installer Pterodactyl sans difficulté en 1 seule ligne de commande :&#x20;

```sh
bash <(curl -s https://pterodactyl-installer.se)
```

Répondez en suite à toutes les questions proposées en anglais, vous pouvez utiliser Google Traduction.\
**Attention, ne mettez pas le SSL sur une IP (IP = 5.9.142.96 | Nom de domaine = Pristis.fr) !!**

**Tutoriel terminé ! En voir plus, c'est ci dessous ! ⬇️**
