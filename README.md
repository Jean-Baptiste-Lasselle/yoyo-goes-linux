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

## OpenShot Video Editor

* Mode d'emploi : 
  * Pour démarrer  l'appli : 
  
  ```bash 
  flatpak run org.openshot.OpenShot
  ```
* Hacker Page : https://flathub.org/apps/details/org.openshot.OpenShot

# Xonotic 


* Mode d'emploi : 
  * Pour démarrer  l'appli (et puis discord, steam...): 
  
  ```bash 
  
  flatpak run org.xonotic.Xonotic
  ```
* Hacker Page : https://flathub.org/apps/details/org.xonotic.Xonotic


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
sudo apt install -y flatpak xdg-desktop-portal-gtk xdg-desktop-portal gnome-software gnome-software-plugin-flatpak

# adding flatpak repos

flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak remote-add --if-not-exists nuvola https://dl.tiliado.eu/flatpak/nuvola.flatpakrepo

# Install Nuvola Apps Service 
flatpak install -y nuvola eu.tiliado.Nuvola

## -->> Now we can install Flatpacked, Nuvola apps
# 
# Launch APP (say Deezer)
export FLAT_PACKED_APP=eu.tiliado.NuvolaAppDeezer
flatpak run $FLAT_PACKED_APP



# Install Deezer 
flatpak install -y nuvola eu.tiliado.NuvolaAppDeezer


# Install Libre Office

flatpak install flathub org.libreoffice.LibreOffice

# Install Steam gamer's hipster platform
flatpak install -y flathub com.valvesoftware.Steam

# Install Vocal 
flatpak install -y flathub com.github.needleandthread.vocal

# Hydra Paper
flatpak install -y flathub org.gabmus.hydrapaper

# OpenShot Video Editor
flatpak install -y flathub org.openshot.OpenShot

# Intall Audacity MSound Mix Table
flatpak install -y flathub org.audacityteam.Audacity

# Discord 

flatpak install -y flathub com.discordapp.Discord

# Xonotic Game
flatpak install -y flathub org.xonotic.Xonotic
```
