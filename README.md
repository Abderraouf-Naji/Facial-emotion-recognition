Facial Emotion Recognition
Ce projet utilise un modèle d'apprentissage profond pour détecter les émotions faciales en temps réel à partir de la vidéo capturée par une webcam. L'application repose sur OpenCV pour le traitement d'image et un modèle pré-entraîné pour la classification des émotions.

Fonctionnalités
✅ Détection en temps réel : Capture les visages via webcam et détecte les émotions en direct.
✅ Modèle pré-entraîné : Chargement via fichiers JSON et HDF5.
✅ Prédiction d'émotions : Classe les émotions en 7 catégories :
Neutre
Joie
Surprise
Tristesse
Colère
Dégoût
Peur
✅ Interface visuelle : Affiche le visage détecté et l'émotion correspondante sur la vidéo en direct.
Prérequis
📌 Python 3.x
📌 OpenCV
📌 Keras
📌 TensorFlow
📌 NumPy
Installation
1️⃣ Clonez ce repository :

git clone https://github.com/Abderraouf-Naji/facial-emotion-recognition.git
2️⃣ Installez les dépendances :
pip install -r requirements.txt
3️⃣ Téléchargez les fichiers nécessaires :
Modèle JSON : fer1.json
Poids du modèle : fer1.h5
Classifieur Haar : haarcascade_frontalface_default.xml
Utilisation
Placez les fichiers JSON, HDF5, et Haar dans le dossier du projet.
Exécutez le script principal :
bash
Copier le code
python facial_emotion_recognition.py
Une fenêtre affichera la vidéo capturée par la webcam avec les émotions détectées en temps réel.
Exemples d'applications
🎯 Analyse des émotions dans les interactions humaines.
🎯 Études comportementales et psychologiques.
🎯 Intégration dans des systèmes interactifs ou des jeux.
Contribution
💡 Les contributions sont les bienvenues !

Ouvrez une issue pour signaler un bug ou proposer une amélioration.
Soumettez une pull request avec vos modifications.
Licence
📜 Ce projet est sous licence MIT.
