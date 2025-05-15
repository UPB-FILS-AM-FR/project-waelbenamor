   Projet Arduino : Feu de Circulation Intelligent
🎯 Objectif du Projet
Ce projet a pour but de simuler le fonctionnement d’un feu de circulation routier intelligent en utilisant une carte Arduino Uno, des LEDs, un capteur de proximité et un buzzer. L’objectif principal est de rendre le système interactif : le feu change automatiquement de phase lorsqu’un piéton ou une voiture est détecté à proximité, et un signal sonore est émis pour indiquer la permission de passage.

 Matériel utilisé
1x Arduino Uno

1x Capteur à ultrasons HC-SR04

3x LED (Rouge, Jaune, Verte)

3x Résistances de 220 ohms

1x Buzzer

Fils de connexion

1x Breadboard (plaque d'essai)

⚙️ Fonctionnement
Par défaut, le feu reste au rouge.

Lorsque le capteur détecte un objet à moins de 50 cm, le feu :

Passe au vert pendant 5 secondes avec un signal sonore (buzzer activé).

Ensuite passe au jaune pendant 2 secondes.

Puis retourne au rouge.

Si aucun objet n’est détecté, le feu reste au rouge et aucun son n’est émis.

📄 Code utilisé
Le programme a été développé en langage Arduino C++ et utilise la bibliothèque NewPing pour faciliter la gestion du capteur HC-SR04.

 Améliorations possibles
Ajout d’un bouton poussoir pour simuler un piéton qui veut traverser.

Intégration d’un écran LCD pour afficher des messages comme "Attendez", "Traversez", etc.

Ajout d’un compteur de temps (affichage du temps restant avant le passage au vert ou au rouge).

 Conclusion
Ce projet va au-delà d’un simple feu tricolore statique. Il propose une interaction dynamique grâce à la détection de proximité et une signalisation sonore, ce qui le rend plus réaliste et utile dans un contexte pédagogique ou de prototypage urbain.
