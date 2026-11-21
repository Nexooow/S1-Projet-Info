# Casier connécté

Casier connecté qui est réservable en ligne par les étudiants ou utilisateurs.
Le but de notre projet est de fournir un système de casier intelligent, potentiellement à placer dans les bibliothèques ou les restaurants universitaires,
pour que les élèves puissent poser leurs affaires si besoin. 

## Installation

Initialiser le projet :
```shell
git clone https://github.com/Nexooow/S1-Projet-Info.git
cd S1-Projet-Info
```

Installer les dépendances et librairies :
```shell
pip install -r "requirements.txt"
```

## Structure

```
├── src/
│   ├── api/                  # API / Backend
│   ├── controllers/          # Gestion des capteurs
│   ├── database/             # Base de données
│   ├── utils/                # Fonctions utilitaires, constantes, etc...
│   ├── web/                  # Site web / frontend
│   └── main.py               # Point d'entrée
│
├── docs/                     # Documentation
└── requirements.txt
```