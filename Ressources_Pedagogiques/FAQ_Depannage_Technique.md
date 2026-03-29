# 🆘 Guide de Secours : Dépannage Technique (FAQ)

> [!NOTE]
> Ne restez pas bloqué ! 99 % des erreurs sur Google Colab se règlent avec les 3 réflexes ci-dessous.

---

### 1️⃣ `ModuleNotFoundError`
*   **Message** : "No module named 'pandas'" (ou un autre nom).
*   **Cause** : La bibliothèque n'a pas été chargée ou la cellule d'import a été sautée.
*   **Solution** : 
    1. Remontez tout en haut du Notebook.
    2. Exécutez la toute première cellule (celle avec les `import`).
    3. Retentez de lancer votre cellule actuelle.

### 2️⃣ `FileNotFoundError`
*   **Message** : "No such file or directory: 'data.csv'".
*   **Cause** : Python ne voit pas votre fichier.
*   **Solution** : 
    > [!IMPORTANT]
    > Avez-vous cliqué sur l'icône Dossier 📁 à gauche sur Colab ?
    > Si vous utilisez Drive, vérifiez que le bouton **"Monter Drive"** a été activé et que vous avez autorisé l'accès.

### 3️⃣ `SyntaxError` (ou la flèche ➡️)
*   **Cause** : Une petite faute de frappe dans le code.
*   **Points à vérifier** :
    *   Une **parenthèse** `(` non fermée `)`.
    *   L'oubli du **deux-points** `:` à la fin d'une boucle `for` ou d'un `if`.
    *   Un nom de variable mal orthographié (ex: `pd.read_csv` vs `pd.readcsv`).

---

## 🛠️ Le Bouton Magique : "Redémarrer le flux"
Si rien ne marche, que la cellule tourne à l'infini ou que l'erreur semble inexplicable :
1. Allez dans le menu **Exécution** (en haut).
2. Cliquez sur **Redémarrer le flux d'exécution**.
3. Relancez tout depuis le début avec **Tout exécuter**.

---

## 💡 Besoin d'une aide humaine ?
> [!TIP]
> Si l'erreur persiste, copiez-la et collez-la sur le [**Forum de l'UE**](https://github.com/agodmer/UE_medecine_IA_OMICS_2026/discussions). 
> C'est là que vos tuteurs et enseignants interviennent pour vous débloquer !
