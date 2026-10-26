# AI Cyber Shield - Mail Gateway & Anti-Spam IA (PFA EMSI)

Ce projet de fin d'année (PFA) a été réalisé à l'EMSI dans le cadre de ma spécialisation en cybersécurité et Cloud Computing[cite: 1].

## 🎯 Objectif du Projet
Conception et déploiement d'un bouclier de messagerie intelligent capable d'intercepter et de filtrer le trafic SMTP en temps réel pour contrer les spams et les menaces par e-mail.

## ⚙️ Architecture & Fonctionnalités
- **Passerelle SMTP :** Interception du trafic en temps réel sous Linux (Sendmail / Milter).
- **Moteur d'IA (NLP) :** Classification des messages à l'aide d'un modèle BERT intégré via une API FastAPI sécurisée par JWT[cite: 1].
- **Dashboard SecOps :** Interface de supervision complète pour le suivi des alertes et des flux (React, Nginx, PostgreSQL, Docker)[cite: 1].

## 🛠️ Stack Technique
* **Sécurité & Réseau :** Sendmail, Milter, SMTP
* **IA & Backend :** Python, BERT (NLP), FastAPI, JWT
* **Frontend & Dashboard :** React, Nginx
* **Infrastructure & Base de données :** Docker, PostgreSQL
