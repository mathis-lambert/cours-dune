[//]: <> (https://stackedit.io/app#)

# Versioning GIT

# Historique des Versions

## [v1.0.0] - Nouveau Projet

### Ajouts
- Premiére version du projet.
- Intégration de la détection YOLO.
- Mise en place de Yolo V4.
- Intégration d'un fichier coco.names et de toutes les dépendances nécessaire au bon fonctionnement de yolo.

### Modifications
- Aucune modification pour cette version.

### Corrections de Bugs
- Aucune correction de bug pour cette version.

## [v1.0.1] - Amélioration / tentative de test

### Ajouts
- Ajout d'OpenPose avec les dépendances nécessaire.
- Ajout d'OpenCV avec les dépendances nécessaire.

### Modifications
- Aucune modification pour cette version.

### Corrections de Bugs
- Correction d'un bug lié au lancement de yolo avec la camera de l'ordinateur.

### Problémes rencontrés
- Version de yolo trop ancienne (v4).
- Version de python trop avancé (3.12.0 -> beta)
- Dépendances manquantes et parfois dépréciés
- 

## [v2.0.0] - Nouvelle version

### Ajouts
- Ajout de nouvelles fonctionnalités.
- Ajout d'un nouveau dossier en local pour stocker la nouvelle version et ses composantes

### Modifications
- Mise à jour vers Ultralytics version 8.0.207
- Mise à jour vers opencv-python version 4.8.1.78.
- Utilisation de np avec Numpy
- Utilisation du model yolov8n-pose.pt 

### Corrections de Bugs
- Correction d'un bug lié à la gestion de yolo avec l'import de la librairie Ultralytics.
- Correction de bug lié au model utilisé par Yolo avec l'import du model yolov8n-pose.pt