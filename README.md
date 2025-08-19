# Debian-Postinstall
Postinstalación debian minimo con el gestor de ventanas fluxbox
## Comando inicial antes de continuar con el proceso
```
$ sudo apt update && sudo apt upgrade
```
## Instalar la sesión de X11 
el primer paso sera instalar x11 y sus utilidades con el siguiente comando
```
$ sudo apt install xorg xdg-utils xdg-user-dirs && xdg-user-dirs-update
```
## Instalar el gestor de inicio de sesión de LightDM
```
$ sudo apt install lightdm lightdm-gtk-greeter lightdm-settings lightdm-gtk-greeter-settings
```
## Instalar servicios esenciales
```
$ sudo apt install dbus dbus-x11 polkitd
```
## Instalar el gestor de ventanas fluxbox y programas basicos
```
$ sudo apt install fluxbox tint2 cbatticon lxappearance xfce4-terminal gthumb dunst zip unzip feh jgmenu thunar mousepad xfce4-screenshooter xfce4-appfinder galculator atril geany firefox-esr firefox-esr-l10n-es-mx
```
## Instalar temas basicos de Gnome (GTK)
```
$ sudo apt install 
```
