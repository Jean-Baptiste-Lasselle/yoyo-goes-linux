# Yoyo goes Linux

Mode d'emploi PC Pour le fils d'un ami

# Modes d'emploi des apps  

## `OpenShot Video Editor` 

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run org.openshot.OpenShot
  ```

* Hacker Page : https://flathub.org/apps/details/org.openshot.OpenShot

## `Deezer` :


* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run eu.tiliado.NuvolaAppDeezer
  ```
* Hacker Page : https://nuvola.tiliado.eu/app/deezer/other/


## Gaming with `Steam` 

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run com.valvesoftware.Steam
  ```
* Hacker Page : https://flathub.org/apps/details/com.valvesoftware.Steam


## `Audacity (Sound Mix and Editor)` 

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run org.audacityteam.Audacity
  ```
* Hacker Page : https://flathub.org/apps/details/org.audacityteam.Audacity

## `Discord (me fait pas croire que tu connait pas)`

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run com.discordapp.Discord
  ```
* Hacker Page : https://flathub.org/apps/details/com.discordapp.Discord
flatpak install flathub com.discordapp.Discord

## OpenShot Video Editor

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run org.openshot.OpenShot
  ```
* Hacker Page : https://flathub.org/apps/details/org.openshot.OpenShot

## Hydra Paper (donenle les droits super utilisateurs pour chambrer son père)


* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  fflatpak run org.gabmus.hydrapaper
  ```
* Hacker Page : https://flathub.org/apps/details/org.gabmus.hydrapaper




## Serious sh*t 

* https://nuvola.tiliado.eu/nuvola/debian/stretch/
* https://flatpak.org/




```bash
sudo apt install flatpak xdg-desktop-portal-gtk xdg-desktop-portal gnome-software gnome-software-plugin-flatpak

# adding flatpak repos

flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak remote-add --if-not-exists nuvola https://dl.tiliado.eu/flatpak/nuvola.flatpakrepo

# Install Nuvola Apps Service 
flatpak install nuvola eu.tiliado.Nuvola

## -->> Now we can oinstall Flatpacked, Nuvola apps
# 

# Install Deezer 
flatpak install nuvola eu.tiliado.NuvolaAppDeezer
# Launch Deezer
flatpak run eu.tiliado.NuvolaAppDeezer

# Install Libre Office

flatpak install flathub org.libreoffice.LibreOffice

# Install Steam gamer's hipster platform
flatpak install flathub com.valvesoftware.Steam

# Install Vocal 
flatpak install flathub com.github.needleandthread.vocal
# Launch Vocal
flatpak run com.github.needleandthread.vocal

# Hydra Paper
flatpak install flathub org.gabmus.hydrapaper
# Run Hydra Paper(to set your coolest wallpapers like the cool guys
flatpak run org.gabmus.hydrapaper

# OpenShot Video Editor
flatpak install flathub org.openshot.OpenShot

# Intall Audacity MSound Mix Table
flatpak install flathub org.audacityteam.Audacity

# Run Audacity MSound Mix Table
flatpak run org.audacityteam.Audacity

# Discord 

flatpak install flathub com.discordapp.Discord

```
