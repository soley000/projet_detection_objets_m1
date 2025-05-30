# Projet M1 — Détection d’objets en image avec Deep Learning

## 📌 Contexte

Ce projet étudiant vise à se former aux outils de **vision par ordinateur** et de **deep learning**. L’objectif est de développer une interface capable de détecter des objets dans des images à l’aide de **modèles pré-entraînés**.

---

## 🧠 Objectifs

- 🎯 Réaliser la détection d’objets à partir d’images importées
- 🧹 Filtrer les détections selon un seuil de confiance réglable
- 📊 Visualiser les résultats directement dans l’interface

---

## 🧰 Modèles utilisés

| Modèle              | Caractéristiques                               |
|---------------------|--------------------------------------------------|
| **YOLOv8n**         | Léger, rapide, exécution locale avec Ultralytics |
| **SSD MobileNet v2**| Chargé depuis TensorFlow Hub, bonne précision    |

---

## 🖥️ Technologies

- Python 3.10+
- Streamlit
- OpenCV
- TensorFlow Hub
- Ultralytics YOLOv8

---

## ⚙️ Lancer l’application

### ✅ En local (recommandé)

```bash
git clone https://github.com/soley000/projet_detection_objets_m1.git
cd projet_detection_objets_m1
pip install -r requirements.txt
streamlit run app.py
```

Une fois lancé, l’application s’ouvrira automatiquement dans votre navigateur à l’adresse http://localhost:8501

### ⚠️ NB : Déploiement en ligne non supporté actuellement
> L’application Streamlit Cloud peut générer une erreur front-end (JavaScript) avec certaines configurations. Il est donc conseillé de l’utiliser **en local uniquement**.

---

## 🧾 Fichiers du projet

- `app.py` : interface Streamlit principale
- `requirements.txt` : bibliothèques nécessaires
- `README.md` : ce fichier
- `images/` : dossier contenant image de test

---

## 👩🏽‍💻 Auteur·e

Projet réalisé par **Rosette-Michèle**  
Étudiante en Master 1 Intelligence Artificielle  
**IA School – Groupe GEMA**
