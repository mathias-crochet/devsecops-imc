# 🛡️ Projet DevSecOps – Master 2

## 🎯 Calcul IMC, CI/CD sécurisé et scan de vulnérabilités

**Étudiants :**  
- Mathias Crochet
- Antoine Rotinat 

**Date :** Juin 2025

---

## 📚 Objectifs pédagogiques

Ce projet a pour but d'initier les étudiants à la démarche **DevSecOps** à travers un cas pratique :

- Développer une application Flask de **calcul de l’IMC**
- Connecter l’application à une base de données **MySQL**
- Conteneuriser le projet avec **Docker**
- Mettre en place un pipeline **CI/CD sécurisé** (GitHub Actions)
- Intégrer des outils de **scan de vulnérabilités** (Trivy, Snyk)
- Publier automatiquement les images sur **DockerHub**

---

## 🗂️ Architecture du projet

```plaintext
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
├── db/
│   ├── init.sql
│   └── Dockerfile
├── .github/workflows/
│   └── ci-cd.yml
├── docker-compose.yml
└── README.md
