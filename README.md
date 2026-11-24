# Installeur du Control Center

Installe le plugin **Control Center** de L'Atelier dans SimHub, en un clic.

## Télécharger

👉 [**ControlCenter-Installeur.exe**](https://github.com/marsouille13/control-center-installeur/releases/latest/download/ControlCenter-Installeur.exe)

Windows 10 ou 11, avec SimHub déjà installé ([simhubdash.com](https://www.simhubdash.com/)).

## Installer

1. Ouvrez le fichier téléchargé, `ControlCenter-Installeur.exe`.
   Si votre navigateur dit que ce fichier est rarement téléchargé, choisissez « Conserver ».
2. Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur « Informations complémentaires », puis sur
   « Exécuter quand même ». Acceptez ensuite la demande d'autorisation de Windows en cliquant sur « Oui ».
3. Cliquez sur « Installer ». L'installeur trouve SimHub, le ferme s'il est ouvert, installe la dernière version du
   Control Center, puis relance SimHub.
4. Si SimHub signale un nouveau plugin, activez-le.
5. Recevez votre clé sur [by-latelier.com/control-center](https://www.by-latelier.com/control-center/), puis collez-la
   sur l'écran « Bienvenue, pilote » du Control Center.

Windows et votre navigateur ne connaissent pas encore l'éditeur de ce fichier : ces avertissements sont normaux pour un
nouveau logiciel.

## Vérifier le fichier

Empreinte SHA-256 de la version 1.1.0 :

```
60bd6764a1100708e006cbe3b2b88f90146369c8d0628fa85f1cbca2c175b1af
```

Dans PowerShell : `Get-FileHash .\ControlCenter-Installeur.exe`

## Ce dépôt

Ce dépôt sert seulement à distribuer l'installeur et l'archive du plugin qu'il installe. Le code du Control Center n'y est pas.
