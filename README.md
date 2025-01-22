# lx-composite-to-minitel

## En

### Description

*Français en dessous*

The goal of this project is to be able to enter a French Minitel with composite video. This project takes back the work from cfp-radio that you can find on their [website]( https://www.cfp-radio.com/realisations/rea48/minitel-01.html).

The cfp-radio project goal was to give audio and video to a Minitel. In my case, I only took the video part. I took back their schematic and made my own PCB all in SMD. All PCB shown in pictures in this repo are manufactured using [PCBWay](https://pcbway.com) services

### KiCad project

The KiCad project can be found under the [av-to-minitel](/av-to-minitel/). The BOM has [mouser](https://www.mouser.ch) reference for all each component.

For the PCB, I created a rounded track version to fit a bit the look of the Minitel PCB with the help of the [kicad-round-tracks](https://github.com/mitxela/kicad-round-tracks) plugin. This PCB is the main PCB [av-to-minitel.kicad_pcb](/av-to-minitel/av-to-minitel.kicad_pcb). The original PCB with normal "square" tracks can be found under the [av-to-minitel-angled.kicad_pcb](/av-to-minitel/av-to-minitel-angled.kicad_pcb) file.

### Assembly

The output connector of the PCB is too small to fit the Minitel board (2.54mm pitch versus 5.08mm pitch). In my case, I unsoldered the original Minitel 5.08 pin header and made a custom adapter cable to fit the Minitel board. See the below picture for more detail.

## Fr

### Description

Le but de ce projet est d'ajouter une entrée composite vidéo à un minitel français. Ce projet reprend le travail de cfp-radio qui peut être retrouvé sur leur site [internet]( https://www.cfp-radio.com/realisations/rea48/minitel-01.html).

Le but du projet de cfp-radio est de rajouter de l'audio et de la vidéo à un minitel. Dans mon cas, je n'ai réalisé que la partie vidéo. J'ai repris leur schématique et réalisé mon propre PCB en smd. Tous les PCBs montrés dans ce repo ont été fabriqués à l'aide des services de [PCBWay](https://pcbway.com).

### Projet KiCad

Le projet KiCad se trouve dans le dossier [av-to-minitel](/av-to-minitel/). La BOM contient des références [mouser](https://www.mouser.ch) pour chaque composant.

Pour le PCB, j'ai utilisé des pistes arrondies pour avoir un style similaire au vieux PCB du Minitel avec l'aide du plugin [kicad-round-tracks](https://github.com/mitxela/kicad-round-tracks). Ce PCB est le PCB principal [av-to-minitel.kicad_pcb](/av-to-minitel/av-to-minitel.kicad_pcb). La version originale avec des pistes "coudées" se trouve dans le fichier [av-to-minitel-angled.kicad_pcb](/av-to-minitel/av-to-minitel-angled.kicad_pcb).

### Assemblage

Le connecteur de sortie du PCB est trop petit pour s'adapter à la carte Minitel (espacement de 2,54 mm contre 5,08 mm). Dans mon cas, j'ai dessoudé le pin header d'origine du Minitel de 5,08mm de pitch et fabriqué un câble adaptateur custom pour s'adapter à la carte Minitel. Voir l'image ci-dessous pour plus de détails.

## Pictures

![top](/pictures/top.jpg)
![bottom](/pictures/bottom.jpg)

## Schematic

![schematic](/av-to-minitel/output/av-to-minitel.svg)