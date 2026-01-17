Système de Gestion de Parking Concurrent

Simulation d'un système de parking démontrant les concepts de **concurrence et synchronisation** dans les systèmes d'exploitation.

Description

Ce projet simule un parking avec un nombre limité de places et plusieurs véhicules accédant simultanément aux ressources. Il illustre l'utilisation de mécanismes de synchronisation pour gérer l'accès concurrent et éviter les conditions de course.

Concepts Illustrés

- **Sémaphores** : Limitation du nombre d'accès simultanés
- **Mutex** : Protection des sections critiques
- **Variables atomiques** : Manipulation sûre des données partagées
- **Multi-threading** : Gestion de threads concurrents


const int DUREE_STATIONNEMENT_MAX = 3;  // Durée max (secondes)
```

Fonctionnalités

- Simulation en temps réel de l'occupation du parking
- Attribution automatique des places disponibles
- Statistiques (temps d'attente, taux d'occupation)
- Affichage synchronisé de l'état du parking

 Objectif

Projet académique illustrant les modèles de concurrence et de synchronisation pour l'accès aux ressources partagées dans les systèmes d'exploitation.
