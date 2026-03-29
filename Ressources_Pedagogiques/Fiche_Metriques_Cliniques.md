# 🩺 Fiche de Synthèse : Métriques de Performance en IA Médicale

> [!IMPORTANT]
> L'évaluation d'un modèle d'IA en santé ne se limite pas à son "score global". En médecine, le coût clinique d'un **Faux Négatif** (ne pas détecter un malade) est souvent bien plus élevé que celui d'un **Faux Positif** (fausse alerte).

---

## 📅 La Matrice de Confusion : Votre Tableau de Bord
Le modèle de Machine Learning classe les échantillons dans un tableau de 4 cases :

| | **Réalité : Malade (+)** | **Réalité : Sain (-)** |
| :--- | :---: | :---: |
| **Prédiction IA : (+)** | **Vrai Positif (VP)** <br> (Malade bien identifié) | **Faux Positif (FP)** <br> (Fausse alerte) |
| **Prédiction IA : (-)** | **Faux Négatif (FN)** <br> (Patient manqué) | **Vrai Négatif (VN)** <br> (Patient sain confirmé) |

---

## 📊 Les 4 Indicateurs Clés à Maîtriser

### 1. La Précision Globale (Accuracy)
*   **Calcul** : $\frac{VP + VN}{\text{Total}}$
> [!WARNING]
> Elle est **trompeuse** si une maladie est très rare (déséquilibre des classes). Si 99 % des patients sont sains, une IA qui répond toujours "Sain" aura 99 % d'accuracy mais sera inutile médicalement.

### 2. Le Rappel ou Sensibilité (Recall / Sensitivity) 🎯
*   **Calcul** : $\frac{VP}{VP + FN}$
*   **Signification** : C'est la capacité du modèle à "ratisser large". 
> [!TIP]
> C'est l'indicateur crucial pour le **dépistage**. Un test très sensible ne laisse passer aucun malade.

### 3. La Précision (Precision)
*   **Calcul** : $\frac{VP}{VP + FP}$
*   **Signification** : Indique la fiabilité d'un test positif. 
*   **En clinique** : Une haute précision signifie que si le test est positif, le patient est **presque certainement** malade.

### 4. Le F1-Score
*   **Calcul** : Moyenne harmonique entre Précision et Rappel.
*   **Usage** : Idéal pour comparer deux modèles quand on veut un bon équilibre entre les deux.

---

## 🚀 Application au Data Challenge (E. coli)
Dans votre challenge MALDI-TOF :
*   Un **Faux Négatif** (classer une bactérie `orec` en `norec`) peut mener à une erreur de prise en charge épidémiologique.
*   Un **Rappel élevé (> 0,90)** est donc l'objectif prioritaire pour garantir la sécurité sanitaire.

> [!NOTE]
> Pour plus de définitions techniques, consultez le [**Glossaire Bio-IA**](./Glossaire_Bio_IA.md).
