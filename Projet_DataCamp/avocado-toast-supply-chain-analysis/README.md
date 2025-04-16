# 🥑 What's in an Avocado Toast: A Supply Chain Analysis
![avocado_wallpaper](https://github.com/user-attachments/assets/5c2dbe7d-3bc0-4140-b2a7-57c59f004082)

## 📌 Objectif du projet

Dans ce projet, j'ai analysé la **chaîne d'approvisionnement** de trois ingrédients couramment utilisés dans un avocado toast :
- 🥑 Avocat
- 🍞 Pain au levain
- 🫒 Huile d'olive extra vierge

Le but était d'identifier les **pays d'origine principaux** de ces produits au Royaume-Uni en s’appuyant sur la base de données ouverte [Open Food Facts](https://world.openfoodfacts.org/).

---

## 📂 Données utilisées

- `avocado.csv` + `relevant_avocado_categories.txt`
- `olive_oil.csv` + `relevant_olive_oil_categories.txt`
- `sourdough.csv` + `relevant_sourdough_categories.txt`

Chaque fichier `.csv` contient des milliers de produits alimentaires, et chaque `.txt` liste les **catégories à retenir** pour filtrer uniquement les produits pertinents.

---

## ⚙️ Compétences mises en œuvre

- Nettoyage et filtrage de données avec **Pandas**
- Utilisation de colonnes contenant des **tags multiples** (`categories_tags`, `origins_tags`)
- Création d’une fonction personnalisée de lecture + filtrage automatisé
- Visualisation rapide des pays d’origine les plus fréquents

---

## 📊 Résultat

J’ai identifié les **pays exportateurs principaux** pour chaque ingrédient vers le Royaume-Uni.  
Cela permet de comprendre l’**impact logistique et géographique** même d’un plat aussi simple qu’un avocado toast.

---

## 💻 Notebook

📎 [👉 Voir le code complet dans le notebook](./avocado-toast-analysis.ipynb)

---

## ✨ Ce projet montre...

🎯 Ma capacité à structurer une analyse de données de A à Z,  
📊 Ma rigueur dans le filtrage et la compréhension des données brutes,  
🚀 Et ma curiosité pour les enjeux concrets des chaînes d’approvisionnement alimentaires.

---

*Projet réalisé dans le cadre de ma formation Data Analyst avec DataCamp.*
