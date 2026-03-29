# 📖 Glossaire : Faire le Pont entre Labo et IA Médicale

> [!NOTE]
> Ce glossaire est votre traducteur de poche pour naviguer entre les termes de microbiologie et les concepts de Science des Données.

---

## 🔬 Termes du Laboratoire (Biologie/Spectrométrie)
*   **Souche (Strain)** : Population bactérienne homogène. C'est votre unité d'analyse.
*   **Spectre MALDI-TOF** : Votre "input". C'est une courbe d'intensité montrant les protéines de la bactérie.
*   **Rapport m/z (Masse/Charge)** : Axe horizontal du spectre. En IA, chaque valeur m/z devient une **colonne** (caractéristique) de votre tableau.
*   **Réplicat Technique / Biologique** : 
    > [!TIP]
    > En Machine Learning, avoir des réplicats est crucial pour vérifier la **robustesse** de votre modèle (est-ce qu'il prédit la même chose sur deux tests du même échantillon ?).

---

## 💻 Termes de Machine Learning (IA)
*   **Target (Cible)** : La réponse attendue (ex: Diagnostiquer `orec` ou `norec`).
*   **Features (Caractéristiques)** : Vos variables d'entrée (ici, les intensités des pics m/z).
*   **Training vs Test Set** :
    *   **Training** : Pour l'apprentissage du modèle.
    *   **Test** : Pour l'évaluation finale (données "neuves").
*   **Overfitting (Sur-apprentissage)** : 
    > [!WARNING]
    > C'est le piège n°1 ! Le modèle connaît le jeu d'entraînement par cœur mais échoue sur de nouveaux patients. C'est l'équivalent d'un étudiant qui apprendrait les réponses du quiz sans comprendre le cours.

---

## 🧮 Méthodes de Réduction
*   **PCA (ACP)** : Algorithme de compression. Indispensable quand on a +3000 pics par spectre.
*   **Standardisation** : 
    > [!IMPORTANT]
    > Toujours standardiser avant un modèle ! Cela permet de comparer des protéines aux intensités très différentes sans que les plus "volumineuses" n'étouffent les autres.

---
[⬅️ Retourner à la Fiche Métriques](./Fiche_Metriques_Cliniques.md) | [🆘 Aide technique](./FAQ_Depannage_Technique.md)
