# Dashboard météo en temps réel avec WebSocket (Node.js + CSV + Chart.js)

 ## Vue d’ensemble
Ce lab met en place une petite application “temps réel” composée de deux parties :
Serveur Node.js : lit le fichier temp.csv, convertit chaque ligne en objet JSON, puis envoie ces objets au navigateur toutes les 3 secondes via WebSocket (port 5002).
Client Web (HTML) : se connecte au WebSocket, reçoit les objets JSON, puis :
ajoute une ligne dans un tableau HTML,
met à jour deux graphiques Chart.js (températures et pluie).

<img width="1916" height="708" alt="image" src="https://github.com/user-attachments/assets/38ee9481-6cd6-48d1-ad49-b19d80c415d8" />

---

## Objectifs pédagogiques
À la fin du lab, il devient possible de :
-Créer un projet Node.js minimal (npm init) et installer les dépendances nécessaires.
-Comprendre le cycle WebSocket : serveur écoute → client se connecte → messages envoyés → messages reçus.
-Transformer des données CSV en objets JavaScript (JSON) côté serveur.
-Construire un tableau HTML dynamique et des visualisations (Chart.js) à partir d’un flux de données.
-Diagnostiquer les erreurs classiques : port occupé, champs CSV incorrects, WebSocket non accessible.

---

## Prérequis
Node.js + npm
Navigateur web
Éditeur de code

---

## Résultat final

<img width="1835" height="1006" alt="image" src="https://github.com/user-attachments/assets/b945d434-0853-4428-ba83-1c4958c29469" />

<img width="1840" height="1010" alt="image" src="https://github.com/user-attachments/assets/2d7e8750-d3c8-4c06-b8fc-ce1331adfff1" />

https://github.com/user-attachments/assets/dec62043-d4c0-458d-98a8-e6248e565f2b

---

## Auteur

**Nom :** JARDI Siham

**Cours :** Développement web full-stack avec JavaScript

**Date :** Janvier 2026

**Encadré par :** Pr.Mohamed LACHGAR









