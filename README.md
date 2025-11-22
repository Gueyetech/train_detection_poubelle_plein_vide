# Détection de Poubelles Pleines/Vides avec YOLOv8

Ce projet utilise YOLOv8 pour détecter et classifier les poubelles comme pleines ou vides.

##  Structure du Projet

```
Poubelles/
├── dataset_detection_poubelle/     # Dataset d'entraînement
│   ├── train/                      # Images d'entraînement
│   ├── valid/                      # Images de validation
│   ├── test/                       # Images de test
│   └── data.yaml                   # Configuration du dataset
├── runs/                           # Résultats d'entraînement
├── poubelle.ipynb                  # Notebook d'entraînement
├── yolov8s.pt                      # Modèle YOLOv8s pré-entraîné
└── yolo11n.pt                      # Modèle YOLO11n pré-entraîné
```

##  Installation

```bash
pip install ultralytics
pip install opencv-python
pip install matplotlib
```

## Entraînement du Modèle

Le notebook `poubelle.ipynb` contient le code d'entraînement complet avec YOLOv8.

### Classes détectées :
- **poubelle_pleine** : Poubelle pleine
- **poubelle_vide** : Poubelle vide

## Projets Associés

- **Application Django** : [detection_poubelle_plein_vide](https://github.com/Gueyetech/detection_poubelle_plein_vide) - Interface web pour la détection en temps réel

## Résultats

Les résultats d'entraînement sont sauvegardés dans le dossier `runs/detect/`.

##  Technologies

- **YOLOv8** - Ultralytics
- **Python 3.11**
- **PyTorch**
- **OpenCV**



