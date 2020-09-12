<p align="center"> 
    <img src="https://zupimages.net/up/20/37/b2cv.png"
        height="130">
</p>

# Fraisiculteur

Bonjour à tous,
je suppose que vous êtes tous là pour fabriquer un super arrosage automatisé à base d'esp32 (et 8266) ? Si oui alors je vais vous montrer comment en fabriquer un !

## Pré-Requis

Pour fabriquer mon arrosage automatisé il vous faut :
- **Esp32 Devkit v1**
- Pompe
- Module relais
- Des fils
- Un capteur DHT22

_**(Optionnel)**_
- Un panneau solaire 24v
- Un controlleur solaire 12-24v
- Une batterie

## Installation

Voici quelques instructions pour installer le programme sur le controlleur Arduino.

1. Installez Le logiciel **Visual Studio Code** en cliquant [ici](https://code.visualstudio.com/)
2. Une fois **Visual Studio Code** installé ouvrez le et cliquez ici :

![extensions visual studio](https://zupimages.net/up/20/37/rwwz.png)

3. Recherchez **"PlatformIO IDE"** dans la barre de recherche, cliquez sur **"Platformio IDE"** et cliquez sur le bouton install si votre Visual Studio est en Anglais. Une fois l'extension installée redémarrez Visual Studio Code et attendez, vous devriez avoir cette page qui va s'ouvrir :

![platformio home](https://zupimages.net/up/20/37/kktl.png)

4. cliquez sur **Open Project**, sélectionnez le code source joint et ouvrez-le

5. Branchez votre carte Esp32 et téléversez le en cliquant ici :

![barre upload](https://zupimages.net/up/20/37/7tx1.png)

attendez la fin de l'upload et débranchez votre carte !

### Et voilà !

## Branchements

Pour continuer à fabriquer ce projet il faut brancher l'esp 32 aux différents modules et capteurs :

![schémas](https://zupimages.net/up/20/37/jcab.png)

## Fabriqué avec
- [Visual Studio Code](https://code.visualstudio.com/)
- C++
- [Platformio IDE](https://platformio.org/platformio-ide)

## Versions

- Dernière version stable : v1.0.1

## Auteurs
- **Enzo Coquuelle** _alias_ [Zoliex35]()
