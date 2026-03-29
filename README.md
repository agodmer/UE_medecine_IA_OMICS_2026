# 🩺 UE : Médecine à l'ère de l'IA et des "Omiques" — 2026

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/fr/2/2c/Logo_sante_horiz_rvb.svg" width="150" alt="Sorbonne Santé">
  <img src="Images/scai_logo.jfif" width="150" alt="SCAI Logo" style="margin-left: 20px;">
  <br><br>
  <img src="https://api.visitorbadge.io/api/combined?path=https%3A%2F%2Fgithub.com%2Fagodmer%2FUE_medecine_IA_OMICS_2026&label=Visiteurs&countColor=%23263159&style=flat" alt="Visiteurs">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fagodmer%2FUE_medecine_IA_OMICS_2026&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Vues&edge_flat=false" alt="Vues">
  <img src="https://img.shields.io/github/stars/agodmer/UE_medecine_IA_OMICS_2026?style=flat&color=gold" alt="Stars">
  <img src="https://img.shields.io/github/forks/agodmer/UE_medecine_IA_OMICS_2026?style=flat&color=blue" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/agodmer/UE_medecine_IA_OMICS_2026?style=flat&color=red" alt="Last Commit">
  <img src="https://img.shields.io/github/languages/count/agodmer/UE_medecine_IA_OMICS_2026?style=flat&color=orange" alt="Languages">
</div>

---

## 📖 Présentation de l'UE

L'évolution rapide des technologies numériques et l'augmentation exponentielle des données en santé (Big Data) transforment radicalement la pratique médicale. Cette unité d'enseignement (UE) a pour objectif de préparer les futurs professionnels de santé à comprendre, manipuler et évaluer de manière critique les outils d'Intelligence Artificielle (IA) et les approches "Omiques" (Génomique, Protéomique, etc.).

À travers un parcours mêlant cours théoriques et ateliers pratiques intensifs, vous apprendrez les fondamentaux de la science des données appliquée au diagnostic médical et à la recherche clinique.

---

## 🚀 Guide de démarrage rapide

| Étapes | Action | Lien utile |
| :--- | :--- | :--- |
| **1** | **Environnement** | Créer un compte [Google Colab](https://colab.research.google.com/) |
| **2** | **Apprentissage** | [Zéro : Guide de démarrage Colab](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/0_Guide_Demarrage_Colab.ipynb) |
| **3** | **Compte GitHub** | Créer un compte [GitHub](https://github.com/join) pour le forum |
| **4** | **Forum de l'UE** | [Discussion & Questions](https://github.com/agodmer/UE_medecine_IA_OMICS_2026/discussions) |
| **5** | **Cheat Sheet** | [Consulter le Mémo Python](Doc_utiles/python_cheatsheets.pdf) |

---

## 💻 Travaux Pratiques (TP) & Notebooks

Les TP sont interactifs et conçus pour être lancés directement sur Google Colab.

| # | Sujet | Notebook (Lien direct Colab) |
| :---: | :--- | :--- |
| 0 | **Zéro : C'est quoi un Notebook ?** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/0_Guide_Demarrage_Colab.ipynb) |
| 1 | **Exploration de données (Partie 1)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/1_TP_Part1_EXPLO.ipynb) |
| 2 | **Exploration de données (Partie 2)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/2_TP_Part2_EXPLO.ipynb) |
| 3 | **Comprendre le Machine Learning** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/3_Comprendre_le_ML.ipynb) |
| 4 | **S'entraîner au Machine Learning** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/4_TD_Part3_ML.ipynb) |
| 📝 | **Fiche Récap : Algorithmes ML** | [Consulter la fiche mémo](TP/5_Fiche_Recap_ML_TD.md) |
| ❓ | **Quiz d'entraînement** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/Quizz/Quiz_MachineLearning_SansCorrection.ipynb) [Correction](Quizz/Quiz_MachineLearning_Corrections.ipynb) |

---

## 🏆 Le Data Challenge

L'évaluation finale repose sur un **Data Challenge** concret basé sur des données réelles de spectrométrie de masse (MALDI-TOF).

### Contexte Scientifique
Lors de l'épidémie de *Escherichia coli* O104:H4 en 2011 (étude [Christner et al. (2014)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0101783)), la rapidité de détection des souches pathogènes a été un enjeu majeur de santé publique. Votre mission est de construire un modèle capable d'identifier automatiquement les souches "tueuses" (`orec`) parmi les souches non épidémiques (`norec`).

### Attendus & Evaluation
- **Notebook complet** : Analyse exploratoire (PCA), Machine Learning (Random Forest, SVM, etc.) et évaluation des performances (Matrice de confusion, F1-score).
- **Restitution** : Présentation par binôme (PowerPoint, 3 diaporamas) devant le jury.
- **Accès au challenge** :  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agodmer/UE_medecine_IA_OMICS_2026/blob/main/TP/6_TP_DataChallenge_MALDI_TOF_version_apprenant.ipynb)

---

## 📅 Programme du séminaire (Avril 2026)

| Jour | Matin (9h-12h) | Après-midi (14h-17h) |
| :--- | :--- | :--- |
| **Mardi 7** | Introduction IA & Recherche bibliographique | Paramétrage & Stats non supervisées |
| **Mercredi 8** | IA & Infertilité, IA & OMICS | Initiation à Python (Partie 1 & 2) |
| **Jeudi 9** | IA & Paludisme, IA & Neurosciences | Comprendre le ML avec Python |
| **Vendredi 10** | Mini-congrès LCA (DFGSM3) | Mini-congrès LCA (DFGSM2) |
| **Lundi 13** | TAL en santé & LLM Prompting | Machine Learning sur données médicales |
| **Mardi 14** | Nephrogénomique & Cardio-IA | Travail personnel |
| **Mercredi 15** | Cytologie Digitale & SIA | **Lancement du Data Challenge** |
| **Jeudi 16** | Travail personnel | Travail personnel |
| **Vendredi 17** | **Évaluation : Soutenances orales** | **Évaluation : Soutenances orales** |

---

## 👤 Responsables de l'UE

- **Dr Alexandre Godmer** (Hôpital Saint-Antoine, CIMI-Paris, Sorbonne-Université)
- **Pr Antonin Lamazière** (Sorbonne-Université)
- **Dr Guillaume Bachelot** (CECOS Tenon, Sorbonne-Université)
- **Dr Orlando Schilton** (Hôpital Trousseau, Sorbonne-Université)

---

<p align="center">
  <i>UE organisée par la Faculté de Médecine de Sorbonne Université.</i><br>
  <i>Support technique via le forum GitHub Discussions.</i>
</p>
