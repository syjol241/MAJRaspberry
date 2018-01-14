echo "$(tput setaf 1)
****************************
** Mise à jour en cours **
** veuillez patienter **
****************************
$(tput sgr 0)"
sudo apt-get update &&
echo "$(tput setaf 6)
****************************
** Update // OK **
****************************
$(tput sgr 0)"
sudo apt-get upgrade -y &&
echo "$(tput setaf 6)
****************************
** Upgrade // OK **
****************************
$(tput sgr 0)"
sudo apt-get dist-upgrade -y &&
echo "$(tput setaf 6)
****************************
** dist-upgrade // OK **
****************************
$(tput sgr 0)"
sudo apt-get clean &&
echo "$(tput setaf 6)
****************************
** clean // OK **
****************************
$(tput sgr 0)"
sudo apt-get autoclean &&
echo "$(tput setaf 6)
****************************
** autoclean // OK **
****************************
$(tput sgr 0)"
sudo rpi-update &&
echo "$(tput setaf 1)
****************************
** MAJ Firmware // OK **
****************************
** ! REBOOT ! REBOOT !**
****************************
$(tput sgr 0)"
sudo reboot