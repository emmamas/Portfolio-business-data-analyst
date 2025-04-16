# 🏍️ Motorcycle Parts Wholesale Revenue Analysis
![motorcycle](https://github.com/user-attachments/assets/bee0491a-c877-432e-a1dd-ec42a59a1637)

## 📊 Objectif du projet

L’objectif est d’analyser les revenus nets générés par les ventes **en gros (Wholesale)** de pièces de moto, en se concentrant sur :

- La répartition des revenus **par ligne de produit**
- Les variations **par mois** et **par entrepôt**
- Le calcul des revenus **nets** après déduction des frais liés aux moyens de paiement

---

## 🧾 Données utilisées

Les données proviennent d’une base de données SQL contenant une table `sales`, avec les colonnes suivantes :

| Colonne | Type | Description |
|--------|------|-------------|
| `order_number` | VARCHAR | Numéro de commande |
| `date` | DATE | Date de la commande (entre juin et août 2021) |
| `warehouse` | VARCHAR | Entrepôt (North, Central, West) |
| `client_type` | VARCHAR | Type de client : Retail ou Wholesale |
| `product_line` | VARCHAR | Type de produit commandé |
| `quantity` | INT | Quantité commandée |
| `unit_price` | FLOAT | Prix unitaire |
| `total` | FLOAT | Prix total |
| `payment` | VARCHAR | Moyen de paiement |
| `payment_fee` | FLOAT | Pourcentage de frais appliqué selon le moyen de paiement |

---

## 🧮 Méthodologie

1. **Filtrer uniquement les commandes “Wholesale”**
2. **Calculer le revenu net** par commande avec la formule : net_revenue = total - (total * payment_fee / 100)

3. **Extraire le mois** à partir de la date (`MONTH(date)`)
4. **Grouper** par :
- `product_line`
- `month`
- `warehouse`
5. **Afficher** les résultats avec la somme du revenu net

---

## 🧰 Compétences & outils utilisés

- SQL (filtres, agrégation, fonctions de date)
- Analyse par groupes (group by)
- Gestion des formats monétaires
- Préparation de données pour reporting Power BI (ou autre outil)

---

## 📎 Résultat

Le tableau obtenu permet aux dirigeants de :
- Visualiser les **produits les plus rentables** en Wholesale
- Suivre l’évolution **mensuelle** des ventes
- Identifier les **performances par entrepôt**

---

## 📄 Fichier associé

📌 [Voir le notebook](./notebook.ipynb)

---

## 🚀 Ce projet démontre :

✅ Une maîtrise des requêtes SQL complexes  
✅ Une capacité à **répondre à un besoin métier concret**  
✅ Une structuration des données pour faciliter la prise de décision

---

*Projet réalisé dans le cadre d’un portfolio Data Analyst.*
