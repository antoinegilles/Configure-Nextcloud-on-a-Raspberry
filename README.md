# Raspberry
![260px-raspberry_pi_logo svg](https://user-images.githubusercontent.com/35256402/49666544-b8d78c00-fa58-11e8-8fdf-1dba01effdcc.png)

This tutorial explains the command lines to install to install NextCloud (a cloud storage) on your raspberry.
Do not hesitate to inform yourself about the ssh connection in order to configure your raspberry remotely.

Here is the link for the connection in ssh : https://the-raspberry.com/ssh-raspberry-pi

three files present:
- install.sh (enumerates the order lists to be performed on a terminal)
- source.txt (the sources that helped us to make this tutorial)

ZSH is part of the order lists, you can ignore this step, it concerns the installation of a new terminal on your raspberry, this is optional.

Lors de la finalisation des étapes, vous n'aurez plus qu'a accéder a votre nextcloud en allant sur http://adressIpPublic/nextcloud 
voici une image : 

<img width="593" alt="capture d ecran 2018-12-07 a 20 58 49" src="https://user-images.githubusercontent.com/35256402/49673595-458d4480-fa6f-11e8-98a6-616cbd5d0a7c.png">

Ils vous demanderont d'utiliser soit sqlLite ou Sqlite/ mariaDB , utilisez MariaDb, vous devrez rentrer le titre de la base de données et le mot de passe. Si vous avez bien suivie l'étape 4 du site https://github.com/antoinegilles/Configure-Nextcloud-on-a-Raspberry vous n'aurez qu'a rentrer les informations en laissant localhost.

Vous voila connecté !
