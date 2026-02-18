# Analyse en Composantes Principales (ACP) – Données Météo HadCRUT

## 📌 Description
Ce projet présente une implémentation complète d’une Analyse en Composantes
Principales (ACP) normée (centrée-réduite) appliquée à des données
climatiques mondiales issues de la base **HadCRUT**.

L’ACP est entièrement reconstruite à partir des **formules théoriques du cours**,
sans utiliser de fonction ACP toute prête.

## 📊 Données
Les données utilisées proviennent de la base publique HadCRUT :
- Source : University of East Anglia
- Données : anomalies de température mensuelles globales

Les individus correspondent aux **années**,
les variables correspondent aux **mois de l’année**.

## 🧠 Méthodologie
Les étapes suivantes sont implémentées manuellement :
- centrage des données
- réduction des données
- construction de la matrice de corrélation
- calcul des valeurs propres et vecteurs propres
- projection des individus et des variables
- interprétation des axes factoriels

## 📈 Visualisations
Le notebook contient :
- visualisation exploratoire des données
- heatmap temporelle
- comparaison avant / après centrage-réduction
- éboulis des valeurs propres
- inertie cumulée
- plan factoriel des individus
- cercle des corrélations
- analyses complémentaires (contributions, cos²)

## 🛠️ Outils
- Python
- NumPy
- Pandas
- Matplotlib

## 🎓 Contexte
Travail réalisé dans le cadre du module **Analyse de Données – RT3**.

## ▶️ Utilisation
Ouvrir le notebook avec **Google Colab** ou **Jupyter Notebook**,
puis exécuter les cellules dans l’ordre.
