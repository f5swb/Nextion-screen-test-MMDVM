
Je vous présente un utilitaire pour les utlisateurs de l'écran NEXTION et du MMDVM.
Celui-ci permet d'afficher tous les champs qui sont disponibles en DMR / 2 TimeSlot.
Les autres modes sont supportés mais la partie graphique n'est pas optimisée.

<img src = "https://github.com/f5swb/Nextion-screen-test-MMDVM/blob/master/SCREEN%20TEST.PNG" title = "Nextion scree">

Deux versions sont disponibles en version 3.5K et 3.5T.

<img src = "https://github.com/f5swb/Nextion-screen-test-MMDVM/blob/master/DMR%20SCREEN%20TEST.PNG" title = "Nextion screen">

L'installation du driver Nextion de EA5KL est indispensable si vous souhaitez avoir toutes les informations.

https://github.com/EA5KL/NextionDriverInstaller

log in to your Pi-Star with SSH

    use PuTTY
    or go to your dashboard -> configuration -> expert -> SSH access (http://pi-star.local/admin/expert/ssh_access.php)

To enable read-write mode:


rpi-rw


The command line prompt will change. from: pi-star@pi-star(ro):tmp$ to: pi-star@pi-star(rw):tmp$


go to the /tmp directory :

cd /tmp

get the software :

git clone https://github.com/EA5KL/NextionDriverInstaller.git

go !

sudo NextionDriverInstaller/install.sh

then reboot you system
