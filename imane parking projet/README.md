
**Licence IDAI 2025-2026**

## 👥 Membres du Groupe
* **imane rhanebou** 
* **Mohamed Zarki**
* **ABDALLAOUI ALAOUI MOHAMED**
# Système de Gestion de Parking Intelligent (Smart Parking System)

Ce projet implémente une simulation de gestion de parking intelligent, incluant des véhicules électriques (EV) et des zones de recharge, en utilisant les principes de la **Programmation Orientée Objet (POO)** en C++ et la bibliothèque graphique **Raylib** pour la visualisation 2D.

---

## 🏗️ Architecture du Projet

Le code est organisé selon la structure modulaire demandée :

| Répertoire | Contenu | POO / Design Patterns |
| :--- | :--- | :--- |
| `include/` | Fichiers d'en-tête (`.h`) pour les classes (`Car`, `ParkingZone`, `ConfigManager`, etc.). | Encapsulation, Héritage (virtuel pour Spot). |
| `src/` | Fichiers d'implémentation (`.cpp`) des classes. | |
| `config/` | Fichier de configuration JSON (simulé) pour les paramètres du jeu. | **Singleton** (pour `ConfigManager`). |
| `demos/` | Point d'entrée de la démo (`main.cpp`) utilisant la classe `Game`. | **State** (pour `GameScreen`). |
| `tests/` | Code source des 5 tests unitaires. | |

## 🛠️ Compilation et Exécution

Le projet utilise un `Makefile` pour la compilation des différents modules.

### Prérequis

* Compilateur C++ (g++).
* Bibliothèque Raylib installée (`/usr/local/raylib/` est le chemin par défaut dans le Makefile).

### 1. Compiler l'application de Démonstration

Pour compiler l'exécutable principal du jeu :

```bash
make clean
make demo
# Exécuter l'application :
./smart_parking_demo
## 🎬 Démonstration
[Cliquez ici pour voir la vidéo de démonstration]
https://drive.google.com/file/d/1qqBNDfhHjkhifUghRueCtFLiz-fj55cg/view?usp=sharing