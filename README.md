# Projet M1 — Détection et reconnaissance d’objets avec Deep Learning

## 📌 Contexte

Ce petit projet étudiant est pour se former sur les outils de détection d'objet..  
Il s’inscrit dans les thématiques de la vision par ordinateur et du deep learning.  
L’objectif est de développer un système de **détection d’objets en image** à l’aide de **modèles pré-entraînés**.

---

## 🧠 Objectifs

- 🎯 Réaliser la détection d’objets
- 🧹 Filtrer les détections peu fiables (score de confiance)
- 📊 Visualiser les résultats et télécharger l’image annotée

---

## 🧰 Modèles utilisés

| Modèle        | Caractéristiques |
|---------------|------------------|
| **YOLOv8n**   | Très rapide, léger, inférence en local |
| **SSD MobileNet v2** | Plus lent, hébergé via TensorFlow Hub, bonne précision |

---

## 🖥️ Technologies

- Python 3.10+
- Streamlit
- OpenCV
- TensorFlow Hub
- Ultralytics YOLOv8

---

##  Comment lancer l’application

### 🔗 Depuis Streamlit Cloud (recommandé)

> 📎 [Clique ici pour voir le projet en ligne](https://ton-lien.streamlit.app)

### 🛠️ En local (optionnel)

```bash
git clone https://github.com/soley000/projet_detection_objets_m1.git
cd projet_detection_objets_m1
pip install -r requirements.txt
streamlit run app.py

