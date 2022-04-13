# 2021-2022_Bahaj_Karmoudi

## Projet Capteur - INSA Toulouse

    Réalisation d'un capteur de déformation low-tech à base de graphite dans le cadre du Projet Capteur de 4ème année Génie Physique à l'INSA de Toulouse.

## Description 

Durant ce projet, nous avons été amenés à concevoir un capteur à jauge de contrainte à base de graphite développé afin de mesurer la résistance en fonction de la courbure appliquée. Une couche de graphite est déposé sur un bout de papier, ce dépôt étant un système granuleux, il existe donc une relation entre la conductivité électrique et l'espace entre les nanoparticules de graphite. Nous avons donc exploité cette propriété afin de relever la variation de la résistance induite par la traction ou la compression du réseau percolé. Pendant ce projet, nous avons été amenés à faire design, la conception et le codage.

## Sommaire

  - [1. Matériel et livrables](#1-Matériel-et-livrables)
      - [1.1 Matériel requis](#11-Matériel-requis)
      - [1.2 Livrables](#12-Livrables)
  - [2. Kicad](#2-Kicad)
      - [2.1 Empreintes des composants](#21-Empreintes-des-composants)
      - [2.2 Schématique](#22-Schématique)
      - [2.3 Création du PCB](#23-Création-du-PCB)
  - [3. Code Arduino](#3-code-arduino)
      - [3.1 Librairies utilisées](#31-Librairies-utilisées)
      - [3.2 Le code](#32-Le-code)
  - [4. Application Bluetooth](#4-application-Bluetooth)
  - [5. Banc de test](#5-Banc-de-test)
  - [6. Datasheet](#6-datasheet)
  - [7. Contact](#6-Contact)

## 1. Matériel et livrables

### 1.1 Matériel

- Carte Arduino UNO
- Une plaque de cuivre pour le Shield
- Papier et crayon à papier
- Un module Bluetooth HC-05 
- Un encodeur rotatoire KY-040
- Un écran OLED
- Deux pinces crocodiles en cuivre pour attacher le capteur au PCB
- Un transistor LTC1050  
- Smartphone Android

### 1.2 Livrables

Les livrables du projet sont comme suit : 

- Un shield PCB contenant un circuit amplificateur transimpédance, un module bluetooth, un écran OLED et un encodeur rotatoire
- Un code Arduino qui permet d'afficher un menu sur l'OLED, de naviguer dans ce même menu grâce à un encodeur rotatoire, d'afficher les mesures de la déformation récoltés sur l'OLED en fonction de l'option d'affichage choisie auparvant, et de les envoyer vers notre Android grâce au module bluetooth
- Une application Android APK qui nous affiche l'état de connexion, nous affiche les valeurs de la tension et de la résistance ainsi qu'une courbe de la résistance aux bornes du capteur en fonction du temps
- Un banc de test (à determiner)
- Une datasheet détaillant les caractéristiques du capteur

## 2. Kicad 

Kicad est un logiciel de conception pour l'électronique qui a permis dans notre cas de créer le Shield pour la carte Arduino UNO. Toutes nos empreintes et plans de notre shield sont disponibles dans [notre-git] (penser à mettre le site)

### 2.1 Empreintes des composants

![Capteur]("C:\Users\karmo\OneDrive\Bureau\2021-2022_Bahaj_Karmoudi\Images capteur\OLED.png")


### 2.2 Schématique

### 2.3 Création du PCB 

## 3. Code Arduino

Ci-joint notre code complet : [Code_Projet_Capteur](https://github.com/Imane-Karmoudi/2021-2022_Bahaj_Karmoudi/tree/main/Code_Projet_Capteur) 

### 3.1 Librairies utilisées

### 3.2 Le code

## 4. Application Bluetooth

## 5. Banc de test

## 6. Datasheet

- Ci-joint la Datasheet détaillant les différentes caractéristiques du capteur [Datasheet](https://github.com/Imane-Karmoudi/2021-2022_Bahaj_Karmoudi/blob/main/Datasheet.pdf) 

## 7. Contact

Pour toutes questions ou informations supplémentaires concernant notre projet, je vous invite à nous contacter par mail : 

- Imane Karmoudi : karmoudi@insa-toulouse.fr
- Fatima Ezzahra Bahaj : Bahaj@insa-toulouse.fr

