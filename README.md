Table des Matières
=

* [Jin Fast Multi-Tools](#Jin-Fast-Multi-Tools)
* [Disclaimer](#Disclaimer)
* [Installation sur Linux](#Installation-sur-Linux)

Jin Fast Multi-Tools
=

cet outils permet de gagner du temps sur certaines commandes qui peuvent mettre du temps a etre taper comme la creation de malware, il permet aussi un petit panel d'outils permettant de sortir des situation ou vous n'avez pas a votre disposition tout vos outils de pentesting habituelles. il permet aussi a moins experimentées de commencer le Ethical Hacking ou l'OSINT avec une plus grande aisance.

![](https://cdn.discordapp.com/attachments/768799213416218625/781194036581105696/jt.PNG)

Disclaimer
=
cet outil a ee developer pour une utilisation legale, notament dans le cadre du developpement personnelle, et de l'apprentisage. Cet outil est gratuit et ne nececite aucune clé d'acces.


Installation sur Linux
=
Il faut avoir `git` et `python3` d'installer sur sa machine
```
    sudo apt install git python3 #sur les distributions utilisant APT
    git clone https://github.com/JinOnGit/fasttools
    decompressez l'archive
    cd JinFMT
    python3 -m pip install -r requirements.txt
    pip install python-nmap
```    

Execution Linux
=
Dans le repertoire JinFMT/, lancez cette commande pour pouvoir lancer L'outil:
```
python3 jt.py
```
Nouveautées version 1.2b
=
Review des fonctionalitées existantes et correction des beugs

Ajout du menue malware


![](https://cdn.discordapp.com/attachments/768799213416218625/781577228420513862/Capture.PNG)


Compatible
=
- Linux
- Windows (soon)

Python version:
=
- Python3

Modules Python
=
- requests
- bs4
- terminaltables
- colorama
- nmap-python
