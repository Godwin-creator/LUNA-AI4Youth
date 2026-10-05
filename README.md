# LUNA - Santé Menstruelle Intelligente pour l'Afrique Francophone

> *LUNA ne remplace pas le médecin. Elle brise le silence 
> là où aucune app globale n'a regardé.*

---

## À propos

LUNA est une Progressive Web App (PWA) de santé menstruelle 
contextualisée pour les jeunes filles et femmes du Togo 
et d'Afrique francophone.

Développée dans le cadre du **Hackathon AI4Youth - 
NEURACTIF Lomé 2026**, LUNA répond à un problème 
documenté par étude terrain : le silence, le tabou 
et l'absence de ressources médicales fiables en langue 
locale autour de la santé menstruelle au Togo.

---

## Les 4 piliers de LUNA

| Pilier | Description |
|--------|-------------|
| **LUNA Cycle** | Modèle prédictif (Régression logistique vs LSTM) pour analyser le cycle et détecter les anomalies cliniques (dysménorrhée, SOPK, endométriose) |
| **LUNA Chat** | Assistant IA trilingue (Français, Éwé, Kabiyè), anonyme, basé sur LLM + RAG gynécologique validé |
| **LUNA Learn** | Bibliothèque de contenus médicaux vulgarisés en 3 langues, partiellement disponible hors ligne |
| **LUNA Connect** | Annuaire de professionnels de santé à Lomé pour orienter vers des soins accessibles |

---

## Équipe

| Membre | Rôle |
|--------|------|
| **Godwin EDOH BEDI** | Lead Tech & Design - Architecture produit & UX |
| **KOSSI Kossivi Tiné** | Backend & Intégration IA - Pipelines ML & API |
| **AMOENI Esther Blessing** | Validation terrain - Santé publique & enquêtes |
| **AFANOU Achille** | Cybersécurité & Architecture sécurisée |

---

## Stack technique

- **Frontend :** Next.js, Tailwind CSS (PWA)
- **Backend :** Python, FastAPI
- **IA :** Gemini API / Claude API + RAG médical
- **ML :** Scikit-learn (Régression logistique), TensorFlow/Keras (LSTM)
- **Base de données :** PostgreSQL + chiffrement bout en bout
- **Déploiement :** Google Cloud Platform (crédits AI4Youth)
- **Versioning :** GitHub

---

## Étude de terrain

Enquête anonyme menée auprès de jeunes filles, femmes 
et professionnels de santé à Lomé, Togo.

- Cible : 50+ réponses minimum
- Outil : Google Forms (anonyme, sans collecte d'email)
- Données collectées : profils de cycle, symptômes, 
  barrières d'accès aux soins, préférences linguistiques, 
  habitudes numériques

> Les résultats seront publiés dans `/docs/etude_terrain/resultats/`

---

## 📁 Structure du projet

```text
LUNA-AI4Youth/
├── docs/                     # Documentation technique et terrain
├── research/                # Datasets et références médicales
├── notebooks/               # Jupyter Notebooks (EDA + modèles ML)
├── src/                     # Code source (frontend + backend)
└── assets/                  # Logo et ressources visuelles
```

---

## Licence

Ce projet est développé dans un cadre académique et 
compétitif. Tous droits réservés - Équipe LUNA 2026.

---

## Contact

- Emails :
  - [edohbedigodwin@gmail.com](mailto:edohbedigodwin@gmail.com)
  - [kossivitinek@gmail.com](mailto:kossivitinek@gmail.com)
  - [achillethales@gmail.com](mailto:achillethales@gmail.com)
  - [amoeniestherblessing@gmail.com](mailto:amoeniestherblessing@gmail.com)

- Hackathon : [AI4Youth NEURACTIF Lomé 2026](https://ai4youth.neuractif.org)