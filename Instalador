#!/bin/bash
################################################################################

echo " SCRIPT DE PRUEBA INSTALACIÓN LIBREOFFICE 4.2 Creado por 0x69666C61=Alfieri"
################################################################################

clear

if [ "$(id -u)" != "0" ]; then
echo "EL SCRIPT DEBE SER EJECUTADO COMO ROOT :("
exit
fi

################################################################################
# INICIO DEL MODULO DE VALIDACION DE SUPERUSUARIO (ROOT)
################################################################################

espeak -ves+male1 --stdout "MODULO DE INSTALACION INICIADO" | aplay -q

################################################################################
# INICIO DEL MODULO DE INSTALACIÓN DE LIBREOFFICE 4.2.0
################################################################################

clear
cd /home/$USERNAME
$ wget -c download.documentfoundation.org/libreoffice/testing/4.2.0/deb/x86/LibreOfficeDev_4.2.0.0.beta1_Linux_x86_deb.tar.gz
clear
cd /home/$USERNAME
apt-get remove libreoffice-core

wget http://downl
$ tar -xzvf LibreOfficeDev_4.2.0.0.beta1_Linux_x86_deb.tar.gz
cd downl

$ cd LibreOfficeDev_4.2.0.0.beta1_Linux_x86_deb/DEBS

$ sudo dpkg -i *.deb
echo "INICIO DE INSTALACIÓN DE LIBRE OFFICE 4.2"
cd ../..

rm -r LibreOfficeDev_4.2.0.0.beta1_Linux_x86_deb.tar.gz
rm -r libreoffice*

clear

################################################################################
# FINAL DEL MODULO DE INSTALACIÓN DE LIBREOFFICE 4.2.0
################################################################################

espeak -ves+male1 --stdout "MODULO FINALIZADO" | aplay -q
