# projet_Power_BI

# PROJET 
Contexte

Vous avez une compétence en Data analyst pour une entreprise fictive de vente de meubles, Meublatex. L'entreprise dispose de plusieurs magasins et vend une large gamme de meubles (tables, chaises, canapés, etc.).  

La direction souhaite une analyse complète de la performance de l’entreprise en se basant sur deux axes :
1.	Les ventes : Suivi des performances commerciales et des tendances.
2.	L’analyse financière : Évaluation de la rentabilité et des dépenses.
Votre mission en tant que Data Analyst est de construire un tableau de bord Power BI interactif permettant d’aider la direction à prendre des décisions stratégiques.


# Objectifs et Analyses Demandées
1. Analyse des ventes :
•	Calculer le chiffre d’affaires total et par magasin.
•	Identifier les produits les plus vendus et les clients les plus rentables.
•	Suivre l’évolution des ventes mensuelles et annuelles.
4. Analyse financière :
•	Comparer les revenus et les dépenses pour identifier la rentabilité de l’entreprise.
•	Suivre la marge bénéficiaire et le bénéfice net.
 
# Livrables Attendues 
•	Un rapport Power BI avec plusieurs pages dédiées à chaque analyse (ventes, finances).
•	Des visualisations claires et interactives (graphiques, cartes, indicateurs KPI…).
•	Des mesures DAX pertinentes (indicateurs standards / cumulés, marge bénéficiaire…).
•	Des filtres dynamiques pour explorer les données selon différents critères (par magasin, par période…). Prioriser l’utilisation des switchers
 
# Bonus (optionnel, pour aller plus loin)
•	Ajouter une prévision des ventes avec les fonctions analytiques de Power BI.
•	Intégrer une segmentation dynamique des clients pour identifier des profils types.
•	Proposer des recommandations basées sur les tendances observées.
 
# ANNEXES

Données disponibles (Tables à fournir aux étudiants)
1.	Table Ventes
o	ID_Vente (clé primaire)
o	Date_Vente
o	ID_Client (clé étrangère vers Clients)
o	ID_Produit (clé étrangère vers Produits)
o	Quantite
o	Prix_Unitaire
o	Mode_Paiement (Carte, Espèces, Virement)
o	ID_Magasin (clé étrangère vers Magasins)
2.	Table Clients
o	ID_Client (clé primaire)
o	Nom_Client
o	Prenom_Client
o	Email
o	Telephone
o	Ville
o	Pays
3.	Table Produits
o	ID_Produit (clé primaire)
o	Nom_Produit
o	Categorie (Table, Chaise, Canapé…)
o	Prix_Achat
o	Prix_Vente
4.	Table Magasins
o	ID_Magasin (clé primaire)
o	Nom_Magasin
o	Ville
o	Pays
5.	Table Dépenses
o	ID_Depense (clé primaire)
o	Date_Depense
o	Categorie_Depense (Loyer, Salaires, Publicité)
o	Montant
o	ID_Magasin (clé étrangère vers Magasins)


