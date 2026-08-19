# virtual-ai-coach

un système de suivi d’exercices avec votre webcam:

1. Capturer le flux vidéo de la caméra.

2. Estimer la posture (pose estimation) du corps humain en temps réel.

3. Définir pour chaque exercice (squat, fente, pompes, etc.) des critères quantitatifs (angles articulaires, positions relatives, phases de mouvement).

4. Détecter la transition entre phase excentrique et phase concentrique pour compter le nombre de répétitions.

5. Évaluer si la forme (le « form ») est correcte à chaque répétition, en comparant les angles et positions mesurés à des seuils définis.

6. Retourner un feedback visuel et/ou audio si l’exécution est incorrecte, ou afficher le décompte des répétitions réussies.

7. Enregistrer les données (nombre de reps, timestamps, taux de réussite) pour un suivi longitudinal.



## Matériel et prérequis logiciels
- Webcam
    un webcam capable de suivre votre mouvement (webcam obsbot tiny 2 lite)
- Environnement Python

    Python ≥ 3.7 (idéalement 3.8 ou 3.9 pour compatibilité bibliothèques récentes).

    Un environnement virtuel (venv, conda, etc.) pour gérer les dépendances.

- Bibliothèques principales

    OpenCV (cv2) pour la capture vidéo, le traitement d’image et l’affichage.

    MediaPipe (module mediapipe) pour la détection de pose en temps réel (pose estimation). MediaPipe Pose fournit les coordonnées 3D approximatives d’une vingtaine de landmarks (points clés) sur le corps.

    NumPy pour les calculs vectoriels sur les points clés.

## Documentation et Développement
  https://docs.google.com/document/d/1I0t6MaOxJ94KUO3kbdNoP-yc5p86Vt0bRTbz3bye8Fc/edit?usp=sharing
