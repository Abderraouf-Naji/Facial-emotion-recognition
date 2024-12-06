Facial Emotion Recognition
Ce projet utilise un modèle d'apprentissage profond pour détecter les émotions faciales en temps réel à partir de la vidéo capturée par une webcam. L'application repose sur OpenCV pour le traitement d'image et sur un modèle pré-entraîné pour la classification des émotions.

Fonctionnalités
Détection en temps réel : Le programme capture les visages à partir d'une webcam et détecte les émotions faciales en temps réel.
Modèle pré-entraîné : Utilise un modèle de réseau neuronal convolutionnel chargé à partir de fichiers JSON et HDF5.
Prédiction d'émotions : Classe les émotions en 7 catégories :
Neutre
Joie
Surprise
Tristesse
Colère
Dégoût
Peur
Interface visuelle : Affiche le visage détecté et l'émotion prédite sur la vidéo en direct.
Prérequis
Python 3.x
OpenCV
Keras
TensorFlow
NumPy
Installation
Clonez ce repository :
bash
Copier le code
git clone https://github.com/Abderraouf-Naji/facial-emotion-recognition.git  
Installez les dépendances :
bash
Copier le code
pip install -r requirements.txt  
Téléchargez les fichiers nécessaires :
Modèle JSON : fer1.json
Poids du modèle : fer1.h5
Classifieur Haar : haarcascade_frontalface_default.xml
Utilisation
Placez les fichiers JSON, HDF5, et Haar dans le dossier du projet.
Exécutez le script principal :
python facial_emotion_recognition.py  
Une fenêtre s'ouvrira avec la vidéo capturée par la webcam et les émotions détectées en temps réel.
Exemples d'applications
Analyse des émotions dans les interactions humaines.
Études comportementales et psychologiques.
Intégration dans des systèmes interactifs ou des jeux.
Contribution
Les contributions sont les bienvenues ! Si vous avez des idées d'amélioration, n'hésitez pas à ouvrir une issue ou soumettre une pull request.
