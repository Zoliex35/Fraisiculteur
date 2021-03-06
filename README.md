﻿<p align="center"> 
    <img src="https://zupimages.net/up/20/37/b2cv.png"
        height="130">
</p>
<p align="center" >
        <img src="https://img.shields.io/badge/Version%20stable-1.0.1-brightgreen" />
        <img src="https://img.shields.io/badge/Version-1.0.1-orange"/>
        <img src="https://img.shields.io/badge/Made%20with-Visual%20Studio%20Code-blue"/>
        <img src="https://img.shields.io/badge/langage-C%2B%2B-blueviolet"/>
        <img src="https://img.shields.io/badge/Licence-CC%20BY--NC--SA%203.0%20FR-yellow"/>
</p>

# Fraisiculteur

Bonjour à tous,
je suppose que vous êtes tous là pour fabriquer un super arrosage automatisé à base d'esp32 (et 8266) ? Si oui alors je vais vous montrer comment en fabriquer un !

Pour commencer téléchargez ce git et décompressez-le

## Pré-Requis

Voici une liste des composants qu'il vous faudra pour fabriquer ce projet (prix: ~ 35€) :

(/!\ lien non aphilié): liste Aliexpress [ICI](https://my.aliexpress.com/wishlist/wish_list_product_list.htm?spm=a2g0s.8937460.0.0.100d2e0ejaGL5q&currentGroupId=1000000000355863)
- Esp32 Devkit v1
- Esp8266
- Pompe
- Module relais
- Des fils
- Un capteur DHT22
- 2 Boutons autobloquants 12mm de Ø
- Un connecteur dc mâle/femelle 12mm de Ø
- Un cable USB
- Un écran LCD I2C 20*4 arduino

_**(Optionnel)**_
- Un panneau solaire 24v
- Un controlleur solaire 12-24v
- Une batterie

# I- Installer **Platformio IDE**

1. Installez Le logiciel **Visual Studio Code** en cliquant [ici](https://code.visualstudio.com/)
2. Une fois **Visual Studio Code** installé ouvrez le et cliquez ici :

![extensions visual studio](https://zupimages.net/up/20/37/rwwz.png)

3. Recherchez **"PlatformIO IDE"** dans la barre de recherche, cliquez sur **"Platformio IDE"** et cliquez sur le bouton install si votre Visual Studio est en Anglais. Une fois l'extension installée redémarrez Visual Studio Code et attendez, vous devriez avoir cette page qui va s'ouvrir :

![platformio home](https://zupimages.net/up/20/37/kktl.png)

Si cela fonctionne passez à l'étape suivante 

# II- Téléverser le code sur les cartes

## serveur

1. cliquez sur **Open Project**, sélectionnez le dossier Fraisiculteur du code source joint, validez. Puis ouvrez-le code qui se trouve dans le dossier src/main.cpp

2. Branchez votre carte Esp32 et téléversez le en cliquant ici :

![barre upload](https://zupimages.net/up/20/37/7tx1.png)

attendez la fin de l'upload et débranchez votre carte !

## télécommande

1. recliquez sur **Open Project**, sélectionnez le dossier Fraisicommande du code source joint, validez. Puis ouvrez-le code qui se trouve dans le dossier src/main.cpp

2. Branchez votre carte esp8266 et téléversez le en cliquant ici :

![barre upload](https://zupimages.net/up/20/37/7tx1.png)

Pareil, attendez la fin et débranchez la !

# III- Branchements

Maintenant il va falloir brancher correctement les cartes aux différents modules arduino :

## serveur

Il faut d'abord brancher la partie "serveur" qui sera la partie qui sera au niveau de nos plantes :

- 1 esp32
- 1 module relais
- un module capteur DHT22
- des fils
- une pompe

![schémas](https://zupimages.net/up/20/37/jcab.png)

## télécommande

Puis la partie client que l'on aura avec nous pour controller les températures et la pompe

- 2 boutons autobloquants 12mm
- 1 prise dc mâle/femelle
- une résistance 10K ohms
- un esp 8266
- un écran lcd 20*4

![schémas](https://zupimages.net/up/20/37/euvi.png)

## Fabriqué avec
- [Visual Studio Code](https://code.visualstudio.com/)
- C++
- [Platformio IDE](https://platformio.org/platformio-ide)
- Fusion 360

## Versions

- Dernière version stable : v1.0.1

## Auteurs
- **Enzo Coquelle** _alias_ [Zoliex35](https://github.com/Zoliex35/)

## Licence
Ce projet est sous la licence Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 3.0 France (CC BY-NC-SA 3.0 FR) - allez voir [ici](https://creativecommons.org/licenses/by-nc-sa/3.0/fr/) pour plus d'infos

<p align="center">
<img src="https://licensebuttons.net/l/by-nc-sa/3.0/fr/88x31.png"/>

</p>
